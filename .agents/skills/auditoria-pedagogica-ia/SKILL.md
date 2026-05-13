---
name: auditoria-pedagogica-ia
description: Use when the user asks to review critically, audit, detect pedagogical bias in, question the didactic assumptions of, or validate an AI-generated pedagogical artifact. Reads a Markdown artifact from the current repo and produces a pedagogical audit in Markdown inside .auditorias_pedagogicas at the repo root.
---

# Auditoria pedagogica de IA

Use this skill when the user wants a critical pedagogical review of an artifact created with AI, especially a lesson plan, activity, rubric, guide, sequence, prompt output, or similar pedagogical document.

## What this skill does

This skill audits a Markdown artifact from the current repository using a rubric derived from Valeria Odetti's concept of `sesgo pedagogico`.

The skill must:

1. Read the artifact from a `.md` path inside the current repo.
2. Audit the artifact with the rubric in `references/sesgo-pedagogico-odetti.md`.
3. Produce a Markdown audit file inside `.auditorias_pedagogicas/` at the repo root.
4. Use the language of the user's current request for the audit text.

## Trigger cues

Use this skill when the user asks to:

- review a pedagogical artifact critically;
- audit an AI-generated lesson or activity;
- detect pedagogical bias or didactic risks;
- question the assumptions behind an educational output;
- validate an AI-generated pedagogical result critically.

## Inputs

Required input:

- a path to a `.md` artifact inside the current repository.

Accepted path forms:

- relative to repo root;
- absolute path inside the repo.

Reject the request with a clear message if:

- the file does not exist;
- the file is not Markdown;
- the file is outside the repo.

## Output location and naming

Write the audit to `.auditorias_pedagogicas/` at the repo root.

Base filename:

- `<artifact-stem>.auditoria-pedagogica.md`

If that file already exists:

- ask the user whether to overwrite it or create a new version;
- do not overwrite automatically;
- if the user chooses a new version, use suffixes like `-2`, `-3`, and so on.

If the folder does not exist, create it before writing the audit.

## Audit workflow

1. Resolve the repo root and normalize the target path.
2. Verify the target file is a Markdown artifact inside the repo.
3. Read the artifact closely.
4. Read `references/sesgo-pedagogico-odetti.md`.
5. Audit the artifact with the required dimensions below.
6. If an audit file already exists, ask the user whether to overwrite or version.
7. Write the final audit as Markdown.

## Required audit dimensions

Always evaluate all of these dimensions:

1. `Concepcion del aprendizaje`
2. `Profundidad cognitiva`
3. `Agencia estudiantil y rol docente`
4. `Contextualizacion situada`
5. `Temporalidad del aprendizaje`
6. `Metarreflexion y criterios`
7. `Neutralidad aparente y universalidad metodologica`

For each dimension, always include:

- `Nivel de riesgo`: `Bajo`, `Medio`, or `Alto`
- `Evidencia del artefacto`
- `Explicacion pedagogica`
- `Recomendacion de ajuste`

## Audit writing rules

- Prioritize critical pedagogical reading over style correction.
- Do not confuse formal polish with pedagogical quality.
- Do not give generic praise.
- If context is missing, name that limitation explicitly.
- Do not assume a better prompt would solve the issue by itself.
- Focus on assumptions about teaching and learning, not only wording defects.
- Use evidence from the artifact, quoting short excerpts when useful.
- Keep artifact excerpts in the original artifact language when citing them.
- Write the audit narrative in the language of the user's current request.

## Required audit structure

Use this exact section structure in the output audit:

```md
# Pedagogical Audit: <artifact title or filename>

## Metadata

- Artifact:
- Source path:
- Audit date:
- Request language:
- Audit basis:
- Scope:

## Executive Summary

## Risk Summary

| Dimension | Risk | Short note |
| --- | --- | --- |

## Findings by Dimension

### 1. Concepcion del aprendizaje

**Nivel de riesgo:** ...

**Evidencia del artefacto:** ...

**Explicacion pedagogica:** ...

**Recomendacion de ajuste:** ...

### 2. Profundidad cognitiva

...

## Prioritized Recommendations

## Critical Questions for Human Review

## Final Verdict
```

## Critical questions

Always include at least these questions, adapted to the request language:

- What do students actually have to do in order to learn this?
- Does the proposal require understanding, analysis, dialogue, or production, or mostly repetition and verification?
- Is the context explicit, or could the sequence be swapped into almost any scenario?
- Are evaluation criteria and reflection moments made explicit?
- Is AI supporting pedagogical decisions or silently replacing them?

## Reference usage

Read `references/sesgo-pedagogico-odetti.md` every time you use this skill.

Use it as the normative basis for:

- identifying pedagogical bias;
- distinguishing artifact quality from pedagogical grounding;
- framing risks and recommendations;
- naming the limits of apparently neutral or universal solutions.
