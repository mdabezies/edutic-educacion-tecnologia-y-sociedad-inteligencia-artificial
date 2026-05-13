# Auditoría pedagógica: Actividad de formación: laboratorio de agent skills para consultoría de software

## Metadatos

- Artefacto: `actividad-agent-skills.md`
- Ruta de origen: `./actividad-agent-skills.md`
- Fecha de auditoría: 2026-05-13
- Idioma de la solicitud: español
- Base de auditoría: rúbrica de sesgo pedagógico basada en Valeria Odetti, con foco en concepción del aprendizaje, profundidad cognitiva, agencia, contextualización, temporalidad, metarreflexión y neutralidad metodológica aparente.
- Alcance: auditoría pedagógica crítica del artefacto completo. No evalúa factibilidad técnica, presupuesto, política institucional ni condiciones reales de implementación más allá de lo explicitado en el documento.

## Resumen ejecutivo

La actividad propone una formación más sólida que una capacitación instrumental centrada en prompts. Su decisión pedagógica más fuerte es desplazar el aprendizaje hacia una práctica situada: seleccionar una tarea real de una consultora, diseñar una `agent skill`, probarla, iterarla, documentarla y reflexionar sobre su valor y sus límites.

El riesgo pedagógico general es medio-bajo. La propuesta evita varios sesgos habituales en el uso educativo de IA: no reduce el aprendizaje a recepción de contenidos, no presenta la herramienta como solución mágica y no invisibiliza del todo la necesidad de criterio profesional. Aun así, conserva zonas a revisar: presupone que la producción de una skill genera transferencia casi por sí misma, explicita poco las diferencias entre perfiles participantes y podría naturalizar la conversión de prácticas laborales en procedimientos reutilizables como si esa formalización siempre fuera deseable.

La mejora principal sería problematizar más el pasaje de práctica profesional a skill: qué se gana, qué se pierde, qué queda fuera de procedimiento y cuándo conviene no automatizar ni formalizar una tarea en una skill.

## Síntesis de riesgos

| Dimensión | Riesgo | Nota breve |
| --- | --- | --- |
| Concepción del aprendizaje | Bajo | Predomina aprender haciendo, aunque conviene explicitar mejor los conceptos que se construyen durante la práctica. |
| Profundidad cognitiva | Bajo | Hay análisis, diseño, prueba, evaluación e iteración; falta trabajar más con dilemas y casos fallidos. |
| Agencia estudiantil y rol docente | Medio | Las personas eligen casos, pero la arquitectura de la experiencia está bastante prefijada. |
| Contextualización situada | Medio | Se parte de tareas reales de consultoría, aunque el contexto institucional queda descrito de forma amplia. |
| Temporalidad del aprendizaje | Bajo | La secuencia semanal tiene progresión clara; el riesgo está en la brevedad para consolidar transferencia. |
| Metarreflexión y criterios | Bajo | Hay reflexión y rúbrica, pero faltan indicadores observables para algunos criterios. |
| Neutralidad aparente y universalidad metodológica | Medio | Advierte límites de IA, pero puede asumir que convertir prácticas en skills es siempre una mejora. |

## Hallazgos por dimensión

### 1. Concepción del aprendizaje

**Nivel de riesgo:** Bajo

**Evidencia del artefacto:** El documento sostiene que las personas aprenden al "producir un artefacto concreto, probarlo, iterarlo y explicarlo" y que la actividad "desplaza el foco desde la recepcion pasiva de conceptos hacia la construccion activa de una solucion".

**Explicación pedagógica:** La propuesta no concibe aprender como escuchar, repetir o aplicar instrucciones cerradas. Hay una lógica activa, situada y orientada a la producción, lo que reduce el sesgo pedagógico tradicional señalado por Odetti. El punto débil es que el aprendizaje queda muy vinculado con lograr un producto útil. Falta explicitar con más fuerza qué conceptos se espera construir durante esa producción: automatización responsable, conocimiento tácito, límites de la proceduralización, trazabilidad, evaluación de salidas y juicio humano.

**Recomendación de ajuste:** Agregar una sección breve de "núcleos conceptuales a construir" durante el laboratorio. Esto ayudaría a que la calidad del aprendizaje no se mida solo por la calidad del entregable final.

### 2. Profundidad cognitiva

**Nivel de riesgo:** Bajo

**Evidencia del artefacto:** La secuencia pide "formular el problema", definir un "criterio de exito", "anticipar errores frecuentes", "identificar fallas, ambiguedades o alucinaciones" y "explicar limites, riesgos y condiciones de uso".

**Explicación pedagógica:** Las tareas demandan análisis, diseño, justificación, prueba e iteración. No se limitan a memorización ni verificación superficial. La actividad tiene potencial para formar criterio profesional en el uso de IA. Sin embargo, podría quedarse en una mejora funcional de instrucciones si no incluye el análisis de fallas reales, tensiones éticas o decisiones controvertidas.

**Recomendación de ajuste:** Incorporar una instancia obligatoria de análisis de un caso fallido: una skill que produzca una salida plausible pero incompleta, riesgosa, sesgada o difícil de auditar. Pedir que se identifique qué decisión técnica, pedagógica u organizacional produjo el problema.

### 3. Agencia estudiantil y rol docente

**Nivel de riesgo:** Medio

**Evidencia del artefacto:** Cada participante o pareja debe "seleccionar una tarea frecuente de la consultora" y convertirla en una skill. El equipo facilitador debe "ayudar a elegir tareas", "promover iteraciones cortas" y "orientar la reflexion".

**Explicación pedagógica:** Hay agencia porque las personas eligen casos y producen un artefacto propio. A la vez, la estructura de la experiencia está muy definida: tiempos, productos, plantilla, criterios y forma de entrega. La agencia puede quedar restringida a escoger un ejemplo dentro de una arquitectura ya cerrada. El rol de facilitación aparece más como acompañamiento general que como intervención didáctica ante obstáculos específicos: diferencias entre perfiles, desacuerdos sobre valor, dilemas de automatización o tensiones entre eficiencia y calidad.

**Recomendación de ajuste:** Incluir decisiones explícitas para participantes: justificar si conviene o no crear una skill, elegir el tipo de evidencia de prueba, proponer criterios específicos del caso y delimitar qué decisiones no deberían delegarse al agente. Para la facilitación, agregar intervenciones esperadas ante conflictos o decisiones difíciles.

### 4. Contextualización situada

**Nivel de riesgo:** Medio

**Evidencia del artefacto:** La propuesta parte de "procesos reales de la consultora" y enumera tareas como "revision de PRs", "triage de incidentes", "armado de propuestas" o "documentacion funcional o tecnica".

**Explicación pedagógica:** La contextualización es una fortaleza declarada, pero todavía opera en un nivel amplio. "Consultora de software" es un contexto relevante, aunque no alcanza para anticipar condiciones concretas: tipos de cliente, confidencialidad, herramientas disponibles, madurez en IA, criterios internos de calidad, idioma de trabajo, diferencias entre roles o restricciones contractuales. Desde la perspectiva de Odetti, una propuesta puede parecer situada y aun así ser trasladable casi intacta a muchos contextos similares.

**Recomendación de ajuste:** Agregar una fase inicial de diagnóstico contextual obligatorio con preguntas sobre datos disponibles, restricciones de seguridad, perfiles participantes, estándares internos, procesos con mayor variabilidad y riesgos de uso.

### 5. Temporalidad del aprendizaje

**Nivel de riesgo:** Bajo

**Evidencia del artefacto:** La actividad se organiza en una semana: día 1 para elección del caso, días 2 y 3 para diseño, días 4 y 5 para prueba e iteración, y días 6 y 7 para cierre y socialización.

**Explicación pedagógica:** La secuencia tiene progresión clara: delimitación, diseño, prueba, iteración y cierre. Esto evita una temporalidad fragmentada de actividades sueltas. El riesgo está en la densidad: entre 4 y 6 horas distribuidas en una semana puede alcanzar para una primera versión, pero no necesariamente para observar transferencia real, discutir fallas con profundidad o consolidar criterios compartidos.

**Recomendación de ajuste:** Añadir una revisión diferida, por ejemplo dos semanas después, para analizar si alguna skill fue usada, descartada o modificada en trabajo real. Esa instancia permitiría distinguir entusiasmo inicial de apropiación efectiva.

### 6. Metarreflexión y criterios

**Nivel de riesgo:** Bajo

**Evidencia del artefacto:** El documento exige "una breve reflexion sobre valor, limites y condiciones de adopcion", criterios de evaluación y una reflexión final sobre "que aprendimos sobre la tarea, sobre la IA y sobre la organizacion del trabajo".

**Explicación pedagógica:** La metarreflexión está presente de manera explícita. También hay criterios pertinentes: pertinencia, claridad, calidad operativa, iteración, criterio profesional y transferencia. Esto reduce el riesgo de delegación didáctica inadvertida en la IA. La limitación es que algunos criterios no están formulados como evidencias observables. Por ejemplo, "criterio profesional" puede quedar como declaración si no se pide mostrar decisiones tomadas, descartes realizados o controles humanos definidos.

**Recomendación de ajuste:** Convertir la rúbrica en indicadores observables. Por ejemplo: "identifica al menos dos escenarios donde la skill no debe usarse", "documenta una falla encontrada y el ajuste realizado", "explicita qué revisión humana es obligatoria antes de usar la salida".

### 7. Neutralidad aparente y universalidad metodológica

**Nivel de riesgo:** Medio

**Evidencia del artefacto:** La actividad propone convertir conocimiento operativo en "procedimientos reutilizables para agentes" y afirma que la organización puede construir "una biblioteca de skills, casos de uso y criterios compartidos".

**Explicación pedagógica:** El documento no cae en una neutralidad ingenua: habla de límites, riesgos y controles humanos. Sin embargo, puede aparecer una universalidad metodológica más sutil: asumir que formalizar prácticas en skills reutilizables es, por defecto, una mejora. Algunas prácticas profesionales dependen de juicio situado, negociación con clientes, lectura política, sensibilidad pedagógica o interpretación contextual difícil de proceduralizar. Allí la skill puede apoyar, pero también empobrecer.

**Recomendación de ajuste:** Incluir como criterio de calidad una decisión negativa posible: justificar cuándo no conviene crear una skill, cuándo conviene una guía humana, cuándo el riesgo supera el beneficio o cuándo la variabilidad del caso requiere deliberación profesional antes que reutilización.

## Recomendaciones priorizadas

1. Agregar un diagnóstico contextual inicial obligatorio antes de diseñar la skill: perfiles, restricciones, datos disponibles, estándares internos, riesgos y condiciones de uso.
2. Incorporar una actividad de análisis colectivo de una skill fallida o riesgosa, para trabajar con errores plausibles y no solo con productos exitosos.
3. Convertir los criterios de evaluación en evidencias observables, especialmente los vinculados con criterio profesional, controles humanos y transferencia.
4. Abrir más agencia en la secuencia: permitir que participantes justifiquen no crear una skill, redefinan el entregable o propongan criterios específicos del caso.
5. Añadir una revisión diferida posterior a la semana de trabajo para evaluar transferencia real y aprendizajes organizacionales.
6. Incluir una pregunta explícita sobre qué saberes tácitos se pierden o se transforman al convertir una práctica en procedimiento reutilizable.

## Preguntas críticas para revisión humana

- ¿Qué tienen que hacer efectivamente las personas participantes para aprender: producir una skill, discutir decisiones, analizar fallas, justificar criterios o transformar una práctica laboral?
- ¿La propuesta exige comprensión, análisis, diálogo y producción, o puede resolverse como una buena documentación de instrucciones?
- ¿El contexto real de la consultora está suficientemente explicitado, o la secuencia podría trasladarse casi intacta a otra empresa de software?
- ¿Los criterios de evaluación y los momentos de reflexión son suficientemente observables durante el proceso?
- ¿La IA está apoyando decisiones pedagógicas y profesionales, o algunas decisiones quedan delegadas silenciosamente en la lógica de la skill?
- ¿Qué margen real tienen las personas participantes para decidir que una tarea no debería automatizarse ni convertirse en skill?
- ¿Qué tensiones organizacionales podrían quedar invisibilizadas si la utilidad y la transferencia se vuelven los criterios dominantes?

## Veredicto final

Requiere revisión.

El artefacto es pedagógicamente consistente y evita varios sesgos frecuentes de propuestas generadas con IA: no se limita a enseñar prompts, no reduce el aprendizaje a recepción de contenidos y no invisibiliza por completo los riesgos de la automatización. Su mejor decisión es articular producción, prueba, iteración y reflexión crítica.

La principal alerta es que la propuesta puede naturalizar la conversión de prácticas laborales en skills reutilizables como horizonte deseable. Para fortalecerla, debería problematizar más esa operación: no todo conocimiento profesional se vuelve mejor cuando se proceduraliza, no toda eficiencia implica buen aprendizaje y no toda transferencia organizacional conserva el juicio situado que la práctica requiere.
