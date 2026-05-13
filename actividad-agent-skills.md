# Actividad de formacion: laboratorio de agent skills para consultoria de software

## 1. Sintesis de la propuesta

Se propone una actividad de una semana, en el marco de una serie de charlas y talleres sobre IA, orientada a que las personas participantes aprendan a disenar, probar y mejorar `agent skills` aplicadas a tareas reales de una consultora multinacional de software.

La actividad se organiza como un laboratorio practico con foco en transferencia al trabajo cotidiano. En lugar de centrarse solo en "usar prompts", invita a examinar que partes del trabajo conviene convertir en procedimientos reutilizables para agentes y cuales requieren seguir dependiendo principalmente de juicio humano situado. El producto final no es solamente una experiencia de exploracion, sino un artefacto aplicable: una skill o una decision fundada de no skillificar una tarea, su documentacion de uso y una breve reflexion sobre valor, limites y condiciones de adopcion.

Nombre sugerido de la actividad: **De prompt a capacidad reusable: laboratorio de agent skills**

## 2. Fundamentacion pedagogica

La propuesta se apoya en cuatro decisiones pedagogicas principales.

### 2.1. Aprendizaje situado

La mejor forma de aprender a usar IA en contextos profesionales no es mediante ejercicios abstractos, sino trabajando sobre problemas autenticos del entorno laboral. Por eso la actividad parte de procesos reales de la consultora: analisis de requerimientos, preparacion de reuniones, documentacion tecnica, revision de PRs, onboarding, soporte a QA, triage de incidentes, armado de propuestas o generacion de material interno.

Desde una perspectiva de aprendizaje situado, el conocimiento se construye mejor cuando las practicas de formacion conservan la logica, restricciones y criterios de calidad del contexto donde luego se aplicaran. En este caso, aprender `agent skills` sobre tareas reales favorece una adopcion mas profunda y menos superficial de la IA.

### 2.2. Aprender haciendo con artefactos

La actividad adopta una logica de taller: las personas aprenden al producir un artefacto concreto, probarlo, iterarlo y explicarlo. Esto desplaza el foco desde la recepcion pasiva de conceptos hacia la construccion activa de una solucion.

En terminos pedagogicos, la skill funciona como objeto de aprendizaje y, al mismo tiempo, como evidencia de aprendizaje. Permite observar si la persona:

- comprende el problema de trabajo;
- sabe descomponer una tarea compleja;
- explicita criterios, pasos y restricciones;
- evalua la salida del agente;
- reconoce limites, riesgos y oportunidades de mejora.

### 2.3. Andamiaje y practica deliberada

El uso competente de IA no surge solo por exposicion. Requiere practica deliberada: definir una tarea, formular instrucciones, testear resultados, identificar fallas y ajustar. Para evitar que la actividad dependa excesivamente de perfiles avanzados, se propone un andamiaje claro:

- ejemplos de tareas candidatas;
- plantilla de diseno de skill;
- criterios de evaluacion;
- espacios breves de intercambio entre pares;
- una instancia final de reflexion sobre calidad y gobernanza.

Este andamiaje reduce la ansiedad inicial, estructura la exploracion y mejora la calidad de las iteraciones.

### 2.4. Transferencia, reflexion y criterio profesional

Una dificultad frecuente en la adopcion de IA es que las personas aprenden comandos puntuales, pero no desarrollan criterio para decidir cuando conviene usar IA, con que resguardos y bajo que condiciones. Por eso la actividad incluye una dimension metacognitiva: no alcanza con que "funcione"; hace falta justificar por que la skill agrega valor, que riesgos introduce, que controles humanos requiere y en que escenarios no deberia usarse.

Esta reflexion es especialmente importante en una consultora, donde la calidad del trabajo, la trazabilidad y el juicio profesional son parte del servicio ofrecido.

## 3. Proposito formativo

Que las personas participantes desarrollen capacidades iniciales para disenar y evaluar `agent skills` utiles, reutilizables y responsables, aplicadas a procesos reales de trabajo en consultoria de software, sin perder de vista los limites de la proceduralizacion y la necesidad de control humano.

## 4. Objetivos de aprendizaje

Al finalizar la actividad, se espera que las personas participantes puedan:

- identificar tareas o microprocesos donde una `agent skill` puede aportar valor real;
- distinguir tareas que no conviene convertir en una skill, o que requieren mediaciones humanas fuertes;
- traducir conocimiento tacito de trabajo en instrucciones explicitas y reutilizables;
- probar una skill en un entorno de uso real o simulado;
- evaluar la calidad de sus resultados segun criterios tecnicos, operativos y eticos;
- documentar condiciones de uso, limites, controles humanos y recomendaciones de mejora.

## 5. Destinatarios y requisitos

Destinatarios sugeridos:

- empleados tecnicos y no tecnicos de una consultora multinacional de software;
- perfiles de desarrollo, testing, devops, producto, analisis, soporte, documentacion, RR. HH., project management y gerencia;
- grupos locales de entre 10 y 30 personas o cohortes regionales de entre 100 y 300 participantes, segun el formato de implementacion.

Requisitos minimos:

- acceso a las herramientas disponibles en la empresa: OpenAI enterprise, Codex, Windsurf y/o Copilot;
- conocimiento basico del proceso de trabajo sobre el que se quiera intervenir, aunque no necesariamente conocimientos previos de IA mas alla de un nivel introductorio;
- disposicion para experimentar, documentar y revisar resultados criticamente.

No se requieren conocimientos previos avanzados sobre IA. Si resulta conveniente una charla introductoria previa, deberia contemplar un lenguaje claro para perfiles tecnicos y no tecnicos, y ofrecer ejemplos diferenciados segun roles.

## 6. Descripcion de la actividad

### Consigna central

Cada participante o pareja debera seleccionar una tarea frecuente de la consultora que hoy demande tiempo, esfuerzo repetitivo o variabilidad innecesaria, y evaluar si conviene convertirla en una `agent skill`, en una especificacion reutilizable de skill para un agente, o si corresponde documentar una recomendacion fundada de no proceduralizarla.

La propuesta resultante debera:

- resolver una necesidad clara;
- tener un usuario objetivo definido;
- incluir instrucciones, contexto, criterios de calidad y restricciones;
- ser probada al menos en un caso realista;
- dejar explicitado que revision humana sigue siendo necesaria;
- quedar documentada para que otra persona pueda entender cuando y como usarla, y tambien cuando no usarla.

### Foco recomendado

La actividad no busca producir "demos llamativas", sino habilidades transferibles al trabajo cotidiano. Conviene orientar la seleccion hacia tareas de alto valor practico y bajo riesgo relativo para una primera exploracion, por ejemplo:

- convertir notas de discovery en historias de usuario mejor estructuradas;
- preparar un primer borrador de plan de testing a partir de requerimientos;
- analizar una PR y proponer una lista inicial de riesgos;
- generar una guia de onboarding tecnico para un proyecto;
- resumir reuniones y traducirlas en acciones y preguntas abiertas;
- proponer escenarios de prueba, criterios de aceptacion o matrices de cobertura;
- asistir en documentacion funcional o tecnica;
- ayudar a preparar propuestas, retrospectivas o reportes.

## 7. Modalidad de trabajo

- Duracion: 1 semana.
- Formato: individual o en parejas.
- Dedicacion estimada: entre 4 y 6 horas distribuidas durante la semana.
- Acompanamiento: un canal asincronico para consultas, una breve instancia sincrona intermedia o final y, si el formato lo permite, una revision diferida posterior para observar transferencia real.

## 8. Secuencia sugerida de la semana

### Dia 1. Lanzamiento y eleccion del caso

Objetivo:
delimitar una tarea concreta y justificar por que vale la pena abordarla con una skill.

Actividades:

- presentacion breve de la consigna;
- seleccion del proceso o microtarea;
- diagnostico contextual inicial: quien usaria la skill, en que pais o equipo, con que restricciones, con que datos, con que riesgos y con que nivel de autonomia;
- formulacion del problema: que duele hoy, para quien, con que frecuencia, con que costo;
- definicion de criterio de exito;
- primera decision: conviene convertir esta practica en skill o conviene conservarla principalmente como practica humana guiada?

Producto esperado:
una ficha breve del caso elegido.

### Dias 2 y 3. Diseno de la skill

Objetivo:
explicitar el conocimiento de trabajo que suele estar disperso o implicito.

Actividades:

- describir el usuario objetivo;
- describir el contexto real de implementacion;
- definir entradas y salidas esperadas;
- redactar instrucciones;
- incluir restricciones, tono, formato y criterios de calidad;
- anticipar errores frecuentes o malas interpretaciones del agente;
- explicitar controles humanos obligatorios y escenarios en los que la skill no deberia usarse.

Producto esperado:
primer borrador de la skill o de la recomendacion fundada de no skillificar la tarea.

### Dias 4 y 5. Prueba e iteracion

Objetivo:
poner la skill en uso, revisar resultados y mejorarla.

Actividades:

- probar la skill con uno o mas casos;
- registrar resultados observados;
- identificar fallas, ambiguedades o alucinaciones;
- analizar al menos un caso fallido, riesgoso o enganiosamente plausible;
- ajustar instrucciones, estructura o controles humanos;
- registrar que saberes tacitos se pierden, se transforman o siguen dependiendo de juicio profesional.

Producto esperado:
version iterada de la skill y evidencia breve de prueba.

### Dias 6 y 7. Cierre y socializacion

Objetivo:
consolidar el aprendizaje y extraer criterios transferibles.

Actividades:

- redactar una sintesis del valor de la skill;
- explicar limites, riesgos y condiciones de uso;
- justificar la decision final: skillificar, no skillificar o dejar la tarea bajo un esquema mixto;
- compartir el caso en una instancia breve de muestra o repositorio comun.

Producto esperado:
entrega final documentada.

### Seguimiento sugerido dos semanas despues

Objetivo:
observar transferencia real y no solo calidad del producto inicial.

Actividades:

- revisar si la skill fue usada, modificada, descartada o reemplazada por otra solucion;
- registrar que problemas aparecieron en el uso real;
- discutir si la formalizacion ayudo, simplifico en exceso o invisibilizo conocimiento profesional importante.

Producto esperado:
nota breve de seguimiento o retroalimentacion diferida.

## 9. Entregables

Cada participante o pareja entrega un unico documento en Markdown o un conjunto breve de documentos en Markdown con estos componentes:

1. Nombre de la skill.
2. Problema o proceso que aborda.
3. Usuario o equipo destinatario.
4. Contexto de uso.
5. Instrucciones principales de la skill.
6. Entradas requeridas.
7. Salida esperada.
8. Criterios de calidad.
9. Riesgos, limites y controles humanos necesarios.
10. Escenarios donde la skill no deberia usarse o donde conviene no skillificar la tarea.
11. Evidencia breve de una prueba, incluyendo al menos un caso fallido o riesgoso.
12. Reflexion final: que aprendimos sobre la tarea, sobre la IA, sobre la organizacion del trabajo y sobre lo que no conviene proceduralizar.

## 10. Criterios de evaluacion

Se sugiere una evaluacion formativa con rubrica simple. Los criterios pueden ponderarse en escala `Inicial / En desarrollo / Logrado / Destacado`.

- Pertinencia: la skill responde a una necesidad real y reconocible del trabajo.
- Claridad: las instrucciones son comprensibles, concretas y reutilizables.
- Calidad operativa: las salidas generadas son utiles para el proposito definido.
- Capacidad de iteracion: se evidencia prueba, revision y mejora.
- Criterio profesional: se reconocen limites, riesgos y necesidad de supervision humana.
- Transferencia: la skill podria ser utilizada o adaptada por otras personas o equipos.

Indicadores observables sugeridos:

- identifica al menos un escenario donde conviene no usar la skill;
- documenta una falla encontrada y el ajuste realizado;
- explicita que revision humana sigue siendo obligatoria;
- justifica por que la tarea elegida es pertinente para perfiles tecnicos, no tecnicos o mixtos;
- describe el contexto real de implementacion con suficiente detalle para evitar soluciones genericas.

## 11. Rol de facilitacion

El equipo facilitador no necesita intervenir como "experto que corrige todo", sino como quien ayuda a formular mejores preguntas, delimitar mejor los casos y sostener criterios de calidad.

Funciones clave de facilitacion:

- ayudar a elegir tareas ni demasiado amplias ni demasiado triviales;
- ayudar a distinguir entre tareas realmente skillificables y tareas que requieren mas mediacion humana;
- recordar que una buena skill no reemplaza juicio profesional, sino que lo apoya;
- promover iteraciones cortas en lugar de largas redacciones iniciales;
- intervenir cuando los perfiles tecnicos y no tecnicos queden desbalanceados en participacion o comprension;
- orientar la reflexion sobre sesgos, errores y control humano;
- recuperar aprendizajes transversales al cierre.

## 12. Riesgos pedagogicos y mitigaciones

- Riesgo: que la actividad se vuelva demasiado tecnica y excluya perfiles no desarrolladores.
  Mitigacion: habilitar casos funcionales, de QA, producto, soporte, documentacion y gestion.

- Riesgo: que se premie la espectacularidad por encima de la utilidad.
  Mitigacion: evaluar pertinencia, claridad y transferencia antes que complejidad.

- Riesgo: que las personas confundan "prompt largo" con "skill de calidad".
  Mitigacion: insistir en pruebas, criterios de salida y documentacion de uso.

- Riesgo: que se invisibilicen limites de privacidad, propiedad intelectual o errores de la IA.
  Mitigacion: incluir explicitamente una seccion de riesgos y controles humanos.

- Riesgo: que se naturalice la idea de que toda practica valiosa debe convertirse en skill reutilizable.
  Mitigacion: pedir una justificacion explicita de por que conviene skillificar la tarea elegida y habilitar como resultado valido una recomendacion fundada de no proceduralizar.

## 13. Valor organizacional de la actividad

Ademas de su valor formativo, esta actividad puede dejar capacidad instalada en la organizacion. Si las entregas se sistematizan en un repositorio comun, la empresa no solo capacita personas: comienza a construir una biblioteca de skills, casos de uso y criterios compartidos para el trabajo con IA.

Esto tiene al menos tres efectos estrategicos:

- acelera la apropiacion practica de las herramientas ya licenciadas;
- transforma aprendizajes individuales en activos reutilizables;
- hace visible donde la IA aporta valor real y donde requiere mayores resguardos.

## 14. Variante sugerida para mayor impacto

Si se quiere aumentar el componente colaborativo, puede agregarse una segunda fase optativa: que cada equipo pruebe la skill creada por otro equipo y deje retroalimentacion sobre claridad, utilidad, facilidad de adopcion y riesgos de uso. Esta variante fortalece la documentacion, la usabilidad y la idea de skill como capacidad compartida, no solo como experimento individual.

## 15. Plantilla base para la entrega de participantes

```md
# Nombre de la skill

## 1. Problema que aborda

## 2. Usuario destinatario

## 3. Situacion de uso

## 4. Entradas necesarias

## 5. Instrucciones de la skill

## 6. Salida esperada

## 7. Criterios de calidad

## 8. Riesgos y limites

## 9. Controles humanos necesarios

## 10. Evidencia de prueba

## 11. Escenarios donde no deberia usarse

## 12. Aprendizajes y mejoras futuras
```

## 16. Cierre

La fortaleza de esta actividad es que combina alfabetizacion en IA, mejora de procesos y produccion de conocimiento organizacional. Pedagogicamente, resulta valiosa porque no separa aprender de hacer, ni innovacion de reflexion critica. En una consultora de software, esa articulacion es especialmente potente: permite formar criterio, no solo entusiasmo; practica util, no solo discurso sobre IA.

Su mejora mas importante en esta version es que no da por supuesto que toda buena practica deba terminar convertida en skill. Eso vuelve la propuesta mas situada, mas critica y mas consistente con una adopcion responsable de IA en contextos de trabajo heterogeneos.
