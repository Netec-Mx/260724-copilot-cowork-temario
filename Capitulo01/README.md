# Taller práctico. El verdadero potencial de Copilot Cowork

## Metadatos

| Campo | Detalle |
|---|---|
| **Duración** | 70 minutos |
| **Complejidad** | Media |
| **Nivel Bloom** | Aplicar y analizar |
| **Módulo** | 2. Taller práctico: El verdadero potencial de Copilot Cowork |
| **Modalidad** | Demostración guiada o práctica acompañada |
| **Herramienta principal** | Microsoft 365 Copilot Cowork |
| **Caso ficticio** | Comercializadora Valle Azul S.A.S. — Expansión del servicio Compra y Recoge |
| **Versión** | 1.0 |

---

## Descripción General

En este taller práctico utilizarás Microsoft 365 Copilot Cowork para desarrollar tres escenarios empresariales conectados entre sí. La práctica comienza con una reunión de seguimiento, continúa con una solicitud estratégica recibida por correo y finaliza con el análisis de indicadores operativos, comerciales y financieros.

En cada escenario agregarás fuentes de Microsoft 365, delegarás una tarea de varios pasos, revisarás el progreso de Cowork, validarás los resultados, aprobarás acciones y configurarás una revisión programada. El propósito es convertir información dispersa en decisiones, planes de acción, comunicaciones y seguimiento continuo.

La empresa, las personas, los correos, las reuniones y los datos utilizados en esta práctica son ficticios.


> ⚠️ **Aviso de privacidad:** Durante todo el laboratorio, utiliza **exclusivamente los archivos de práctica proporcionados por el facilitador**. No ingreses datos reales, confidenciales o sensibles de tu organización en ninguna instrucción o prompt de Copilot.

---

## Objetivos de Aprendizaje

Al finalizar este laboratorio serás capaz de:

- [ ] Analizar una reunión, su conversación relacionada y el contexto del caso para identificar acuerdos, decisiones, riesgos y compromisos.
- [ ] Generar un resumen ejecutivo y una lista estructurada de acciones con responsables, fechas, dependencias y criterios de cierre.
- [ ] Preparar borradores de correo, mensajes de coordinación y una reunión de seguimiento, revisando cada acción antes de aprobarla.
- [ ] Consolidar una solicitud estratégica recibida por correo con información relacionada de Teams, OneDrive y Excel.
- [ ] Detectar tendencias, anomalías y variaciones significativas en un archivo de indicadores.
- [ ] Relacionar los resultados numéricos con evidencias procedentes de reuniones, conversaciones y correos.
- [ ] Configurar revisiones programadas que destaquen cambios, riesgos, retrasos y decisiones pendientes.
- [ ] Validar que los resultados diferencien hechos confirmados, inferencias e información por confirmar.

---

## Prerrequisitos

### Conocimientos Previos

| Área | Nivel Requerido |
|---|---|
| Uso de Microsoft 365 Copilot | Básico — envío de solicitudes, incorporación de fuentes y revisión de resultados |
| Microsoft Teams | Básico — reuniones, chats y canales |
| Microsoft Outlook | Básico — lectura de cadenas, borradores y calendario |
| Microsoft Excel | Básico — apertura de libros, tablas y hojas |
| Microsoft Word | Básico — apertura y revisión de documentos |
| OneDrive o SharePoint | Básico — carga, búsqueda y apertura de archivos |

### Acceso y Licencias Requeridas

| Recurso | Estado Requerido |
|---|---|
| Licencia de Microsoft 365 Copilot | ✅ Activa y asignada al participante |
| Cowork habilitado en el entorno | ✅ Confirmado por el administrador o el facilitador |
| Facturación basada en uso para Cowork | ✅ Habilitada por el administrador |
| Anthropic como subprocesador | ✅ Habilitado en el tenant |
| Cuenta organizacional de Microsoft 365 | ✅ Con sesión iniciada |
| Microsoft Teams | ✅ Acceso a reuniones y conversaciones del laboratorio |
| Microsoft Outlook | ✅ Acceso al correo y calendario del laboratorio |
| OneDrive o SharePoint | ✅ Permiso para cargar y consultar los archivos |
| Aplicaciones Word y Excel | ✅ Disponibles en versión web o de escritorio |
| Materiales del repositorio | ✅ Descargados antes de comenzar |


---

## Entorno de Laboratorio

### Hardware Recomendado

| Componente          | Mínimo                                      | Recomendado                                |
|---------------------|---------------------------------------------|--------------------------------------------|
| Procesador          | Intel Core i5 / AMD Ryzen 5 (64 bits)       | Intel Core i7 / AMD Ryzen 7 o superior     |
| Memoria RAM         | 8 GB                                        | 16 GB                                      |
| Resolución pantalla | 1280 × 768                                  | 1920 × 1080                                |
| Conexión a internet | 10 Mbps estable                             | 25 Mbps o superior (red corporativa)       |

### Software Requerido

| Aplicación | Requisito |
|---|---|
| Microsoft 365 Copilot | Aplicación web en `https://m365.cloud.microsoft` o aplicación de escritorio |
| Microsoft Teams | Versión web o de escritorio con sesión iniciada |
| Microsoft Outlook | Versión web o de escritorio con sesión iniciada |
| Microsoft Word | Versión web o de escritorio |
| Microsoft Excel | Versión web o de escritorio |
| Microsoft Edge o Google Chrome | Versión vigente compatible con Microsoft 365 |

### Archivos del Taller

| Archivo | Uso |
|---|---|
| `materiales/01_Reunion_y_contexto.docx` | Contexto empresarial, guion completo de la reunión, participantes y conversación posterior de Teams |
| `materiales/Correos/*.eml` | Siete mensajes ficticios preparados para importación masiva en el nuevo Outlook |
| `materiales/03_Indicadores_operativos.xlsx` | Indicadores operativos, comerciales, financieros, tecnológicos y de experiencia del cliente |

### Preparación del Entorno Antes de Comenzar

Realiza esta preparación antes de iniciar los escenarios. El tiempo asignado dentro del taller es de **5 minutos**.

#### 1. Preparar la carpeta de trabajo

```text
1. Abre OneDrive con tu cuenta organizacional.
2. Crea una carpeta llamada: Taller-Cowork-Expansion.
3. Abre la carpeta materiales del repositorio.
4. Carga en OneDrive:
   - 01_Reunion_y_contexto.docx
   - 03_Indicadores_operativos.xlsx
5. Confirma que ambos archivos pueden abrirse desde el navegador.
```

#### 2. Preparar las fuentes de Microsoft 365

Para una demostración completa, prepara las fuentes antes de la sesión.

```text
Reunión y Teams
1. Crea una reunión titulada:
   Expansión Compra y Recoge - Seguimiento operativo.
2. Inicia la reunión y activa la transcripción en español.
3. Utiliza la sección "Transcripción sugerida" de 01_Reunion_y_contexto.docx
   como guion.
4. Finaliza la reunión y comprueba que la transcripción esté disponible.
5. Publica en el chat de la reunión los mensajes de la sección
   "Conversación posterior en Teams".
6. Conserva 01_Reunion_y_contexto.docx en OneDrive como contexto de referencia.

Outlook - nuevo Outlook para Windows
1. Extrae los siete archivos de materiales/Correos en una carpeta local.
2. Asegúrate de que los archivos .eml estén directamente en esa carpeta,
   no dentro de subcarpetas.
3. En el nuevo Outlook, abre Configuración > General > Importar.
   En algunas versiones la ruta aparece como Configuración > Archivos > Importar.
4. Selecciona Iniciar importación.
5. Selecciona la carpeta que contiene los siete archivos .eml.
6. Elige la cuenta y la carpeta de destino.
7. Selecciona Importar y confirma que la conversación aparece con el asunto:
   Expansión Compra y Recoge - Decisiones y plan de estabilización.

Excel
1. Conserva 03_Indicadores_operativos.xlsx en OneDrive.
2. Abre el libro y confirma que aparecen las hojas Indicadores, Metas,
   Tecnologia, Presupuesto, Resumen y Diccionario.
```

Los archivos también pueden adjuntarse directamente en Cowork cuando la integración con una fuente de Microsoft 365 no esté disponible durante la práctica.

#### 3. Abrir las aplicaciones necesarias

```text
Mantén abiertas las siguientes aplicaciones:
- Microsoft 365 Copilot Cowork
- Microsoft Teams
- Microsoft Outlook
- OneDrive
- Microsoft Word
- Microsoft Excel
```

---

## Instrucciones Paso a Paso

---

### Parte 1: Preparar la sesión de Copilot Cowork

**Tiempo estimado:** 5 minutos

#### Paso 1.1 — Abrir Cowork y crear una tarea

**Objetivo:** iniciar una sesión y reconocer los elementos que se utilizarán durante los tres escenarios.

**Instrucciones:**

1. Abre `https://m365.cloud.microsoft` o la aplicación de escritorio de Microsoft 365 Copilot.
2. Selecciona **Cowork** en la parte superior de la aplicación.
3. Inicia una nueva tarea.
4. Localiza el botón **+** o la opción para adjuntar fuentes.
5. Comprueba que puedes seleccionar archivos del dispositivo, OneDrive, SharePoint o Teams.
6. Abre el panel lateral de la sesión.
7. Identifica los apartados de progreso, archivos de entrada, archivos de salida, aptitudes, programación y permisos.
8. Mantén esta sesión abierta para iniciar el primer escenario.

**Resultado Esperado:**

La página de Cowork muestra una nueva tarea preparada para recibir instrucciones. El panel lateral permite seguir el progreso, revisar las fuentes, abrir los archivos generados y administrar las programaciones y permisos de la sesión.


---

### Parte 2: De la reunión a la ejecución

**Tiempo estimado:** 20 minutos

#### Paso 2.1 — Agregar la reunión y el contexto relacionado

**Objetivo:** reunir en una misma tarea las fuentes que Cowork utilizará para analizar el caso, crear entregables y preparar acciones posteriores.

**Instrucciones:**

1. En Cowork, selecciona la opción para agregar contexto o adjuntar archivos.
2. Agrega la reunión **Expansión Compra y Recoge - Seguimiento operativo**.
3. Agrega la conversación posterior de Teams asociada a la reunión.
4. Agrega `01_Reunion_y_contexto.docx` desde OneDrive.
5. Comprueba en la carpeta de entrada del panel lateral que las fuentes fueron incorporadas.
6. Abre la vista previa del documento y confirma que corresponde al caso de Comercializadora Valle Azul S.A.S.

**Resultado Esperado:**

Cowork dispone de la transcripción, la conversación posterior y el contexto empresarial necesarios para identificar decisiones, compromisos, riesgos y dependencias.


#### Paso 2.2 — Delegar el análisis y la preparación de acciones

**Objetivo:** transformar la reunión en un resumen ejecutivo, acciones de seguimiento y comunicaciones.

**Instrucciones:**

1. Copia el siguiente prompt en Cowork.
2. Revisa que los nombres de las fuentes coincidan con los elementos agregados.
3. Envía la solicitud.

```text
Actúa como coordinador ejecutivo de la expansión del servicio Compra y Recoge.

Analiza la reunión, la conversación posterior de Teams y el contexto empresarial
proporcionado.

Realiza estas actividades:

1. Identifica las decisiones, acuerdos, compromisos, riesgos, bloqueos y dependencias.
2. Diferencia claramente los hechos confirmados, las inferencias y la información
   que todavía debe validarse.
3. Crea un resumen ejecutivo en Word de máximo dos páginas, orientado a la toma
   de decisiones.
4. Incluye una tabla de acciones con:
   - actividad;
   - responsable;
   - fecha objetivo;
   - dependencia;
   - estado inicial;
   - criterio de cierre;
   - fuente que respalda la acción.
5. Prepara un borrador de correo para los participantes con las decisiones y las
   acciones asignadas.
6. Prepara una reunión de revisión de 25 minutos para el próximo martes con los
   participantes del caso y una agenda de tres puntos.
7. Destaca los tres riesgos que la dirección debe vigilar durante la próxima semana.

Muéstrame el plan de trabajo. Solicita mi aprobación antes de crear la reunión,
enviar un correo o publicar un mensaje.
```

4. Observa los pasos que Cowork registra en el panel de progreso.
5. Responde las preguntas de aclaración utilizando únicamente los datos de las fuentes.
6. Espera a que Cowork genere el resumen y las vistas previas de las acciones.

**Resultado Esperado:**

Cowork genera un resumen ejecutivo, una tabla de acciones, un borrador de correo y la propuesta de una reunión de seguimiento. Las acciones sensibles quedan pendientes de revisión y aprobación.

![Análisis contextual](../images/1.png)

#### Paso 2.3 — Revisar, refinar y aprobar

**Objetivo:** validar la precisión de los resultados antes de permitir acciones en Microsoft 365.

**Instrucciones:**

1. Abre el documento generado desde la carpeta de salida.
2. Comprueba cada cifra, responsable y fecha contra las fuentes.
3. Revisa la vista previa del correo.
4. Revisa la vista previa de la reunión.
5. Utiliza el siguiente prompt cuando encuentres información no respaldada:

```text
Revisa nuevamente las fuentes. Conserva únicamente los datos respaldados.
Marca como "Por confirmar" cualquier responsable, fecha, causa, dependencia o
compromiso que no esté indicado explícitamente. Mantén sin cambios los elementos
que sí cuentan con evidencia.
```

6. Solicita los cambios necesarios.
7. Aprueba la creación de la reunión cuando los participantes, la fecha y la agenda sean correctos.
8. Conserva el correo como borrador o aprueba su envío según las indicaciones del facilitador.

**Resultado Esperado:**

El resumen y las acciones quedan respaldados por las fuentes. Las acciones externas se ejecutan únicamente después de revisar la vista previa correspondiente.


#### Paso 2.4 — Programar el seguimiento semanal

**Objetivo:** configurar una revisión periódica que detecte avances, vencimientos y nuevos riesgos.

**Instrucciones:**

1. Envía el siguiente prompt en la misma sesión:

```text
Programa una revisión semanal cada lunes a las 8:00.

En cada ejecución, revisa la reunión, la conversación de Teams, los archivos del
caso, los correos relacionados y el calendario.

Genera una actualización con:
- acciones vencidas o próximas a vencer;
- cambios de estado desde la última revisión;
- nuevos riesgos o bloqueos;
- decisiones que requieren intervención;
- fuentes que respaldan cada cambio;
- un borrador de correo de seguimiento.

Destaca únicamente cambios ocurridos desde la ejecución anterior. Solicita mi
aprobación antes de enviar comunicaciones o modificar elementos de Microsoft 365.
```

2. Revisa la programación propuesta.
3. Confirma la frecuencia, la hora y las fuentes.
4. Selecciona **Activar y ejecutar ahora** para comprobar el comportamiento inicial.
5. Revisa el resultado de la primera ejecución.

![Programación de revisión](../images/2.png)

**Resultado Esperado:**

La tarea aparece en la sección de programaciones y ejecuta una primera revisión basada en las fuentes del caso.

---

### Parte 3: Del correo a la coordinación

**Tiempo estimado:** 20 minutos

#### Paso 3.1 — Agregar la solicitud estratégica y sus fuentes relacionadas

**Objetivo:** reunir en una sola tarea el requerimiento, las respuestas de las áreas y el contexto del piloto.

**Instrucciones:**

1. Inicia una nueva tarea en Cowork.
2. Agrega la cadena de Outlook con el asunto **Expansión Compra y Recoge - Decisiones y plan de estabilización**.
3. Confirma que la cadena contiene los siete mensajes importados.
4. Agrega la reunión y la conversación de Teams utilizadas en el escenario anterior.
5. Agrega `01_Reunion_y_contexto.docx` y `03_Indicadores_operativos.xlsx`.
6. Revisa la carpeta de entrada y confirma que todas las fuentes pertenecen al mismo caso.

**Resultado Esperado:**

Cowork cuenta con la solicitud de Dirección Comercial, las respuestas de Operaciones, Tecnología, Logística, Calidad y Finanzas, el consolidado de coordinación, la reunión y los indicadores del caso.


#### Paso 3.2 — Consolidar antecedentes y preparar una recomendación

**Objetivo:** convertir la cadena de correos y sus fuentes relacionadas en una respuesta ejecutiva y un plan coordinado.

**Instrucciones:**

1. Copia y envía el siguiente prompt:

```text
Actúa como responsable de coordinación de la solicitud estratégica sobre la
expansión del servicio Compra y Recoge.

Analiza la cadena de correo y todas las respuestas relacionadas. Complementa el
análisis con la reunión, la conversación de Teams y el archivo de indicadores.

Realiza estas actividades:

1. Resume el requerimiento, los antecedentes, el criterio de decisión y la fecha límite.
2. Identifica dependencias, riesgos, información faltante y áreas responsables.
3. Relaciona cada afirmación importante con la fuente que la respalda.
4. Distingue las causas confirmadas de las hipótesis todavía abiertas.
5. Propón una recomendación ejecutiva que indique una de estas opciones:
   - avanzar;
   - mantener la expansión en espera;
   - avanzar bajo condiciones verificables.
6. Define las condiciones mínimas y medibles para aplicar la recomendación.
7. Crea un plan de trabajo con:
   - actividad;
   - responsable sugerido;
   - fecha objetivo;
   - dependencia;
   - evidencia requerida;
   - hito de revisión.
8. Prepara un borrador de respuesta para la directora Comercial.
9. Prepara mensajes de coordinación específicos para Logística, Calidad,
   Comercial y Finanzas.

Muéstrame la recomendación y el plan antes de ejecutar acciones. Solicita mi
aprobación antes de enviar correos o publicar mensajes.
```

2. Sigue el progreso en el panel lateral.
3. Revisa las fuentes citadas por Cowork.
4. Abre el documento o la respuesta estructurada generada.

![Antecedentes y recomendación](../images/3.png)

**Resultado Esperado:**

Cowork consolida los antecedentes, identifica las dependencias, propone una recomendación respaldada, crea un plan de trabajo y prepara comunicaciones diferenciadas por área.

#### Paso 3.3 — Validar la recomendación y las comunicaciones

**Objetivo:** asegurar que la respuesta ejecutiva no mezcle hechos comprobados con suposiciones.

**Instrucciones:**

1. Revisa la recomendación contra el resumen de indicadores.
2. Comprueba que el costo estimado de la alternativa logística no supera la contingencia indicada.
3. Comprueba que la afectación logística de Norte esté separada del problema de calidad de Sur.
4. Comprueba que el 7,8 % de no conformidades se presente como resultado de una muestra de 385 pedidos.
5. Comprueba que la contingencia de COP 20.000.000 aparezca como pendiente de aprobación.
6. Comprueba que la propuesta logística de COP 18.600.000 esté condicionada a aceptación y evidencia.
7. Revisa el tono y los destinatarios de cada mensaje.
8. Utiliza este prompt para corregir el resultado:

```text
Ajusta la recomendación para que cada condición sea verificable mediante un
indicador, una fecha y una evidencia. Separa en tres apartados:
1. Hechos confirmados.
2. Hipótesis pendientes de validación.
3. Información faltante para decidir.

Mantén sin cambios las cifras respaldadas por las fuentes.
```

9. Aprueba únicamente los borradores o mensajes indicados por el facilitador.

**Resultado Esperado:**

La recomendación presenta una lógica verificable y las comunicaciones son consistentes con las evidencias del caso.


#### Paso 3.4 — Programar la revisión diaria del caso

**Objetivo:** detectar nuevas respuestas, documentos y cambios relevantes sin repetir búsquedas manuales.

**Instrucciones:**

1. Envía el siguiente prompt:

```text
Programa una revisión diaria a las 16:00 hasta el próximo viernes.

En cada ejecución, revisa la cadena de Outlook, las conversaciones relacionadas,
los documentos agregados y los indicadores del caso.

Genera una actualización ejecutiva que indique:
- qué cambió desde la ejecución anterior;
- qué dependencia fue resuelta;
- qué información continúa pendiente;
- qué riesgo aumentó o disminuyó;
- qué evidencia nueva apareció;
- qué decisión necesita atención.

Prepara un borrador de actualización para la directora Comercial y solicita
mi aprobación antes de enviarlo.
```

2. Revisa las fechas de inicio y finalización.
3. Confirma la hora de ejecución.
4. Activa la programación.
5. Ejecuta una primera revisión para validar el formato.

![Programación de revisión diaria](../images/4.png)

**Resultado Esperado:**

Cowork crea una programación temporal que resume únicamente cambios relevantes y prepara una actualización ejecutiva para revisión.

---

### Parte 4: De los datos a la toma de decisiones

**Tiempo estimado:** 20 minutos

#### Paso 4.1 — Agregar el libro de indicadores y las fuentes de contexto

**Objetivo:** analizar los resultados numéricos junto con la información que explica su comportamiento.

**Instrucciones:**

1. Inicia una nueva tarea en Cowork.
2. Agrega `03_Indicadores_operativos.xlsx`.
3. Agrega la reunión de Teams y `01_Reunion_y_contexto.docx`.
4. Agrega la cadena de Outlook importada desde los archivos `.eml`.
5. Abre la vista previa del libro.
6. Confirma que Cowork puede consultar las hojas **Indicadores**, **Metas**, **Tecnologia**, **Presupuesto**, **Resumen** y **Diccionario**.

**Resultado Esperado:**

Cowork dispone de las cifras del piloto y de las fuentes necesarias para investigar sus posibles causas y consecuencias.

#### Paso 4.2 — Delegar el análisis de indicadores

**Objetivo:** identificar tendencias, anomalías y desviaciones, y relacionarlas con evidencias del caso.

**Instrucciones:**

1. Copia y envía el siguiente prompt:

```text
Actúa como analista ejecutivo del piloto de Compra y Recoge.

Analiza el archivo de indicadores y relaciona los hallazgos con la reunión,
la conversación de Teams y la cadena de correos proporcionadas.

Realiza estas actividades:

1. Identifica tendencias, anomalías y variaciones significativas por región y semana.
2. Compara entregas a tiempo, devoluciones, no conformidades, backlog, costo logístico,
   tiempo de preparación y CSAT con las metas definidas en el libro.
3. Explica qué está ocurriendo en cada región.
4. Diferencia:
   - causas confirmadas por las fuentes;
   - causas probables;
   - hipótesis pendientes de validación.
5. Describe las posibles consecuencias operativas, financieras, comerciales y
   de experiencia del cliente.
6. Propón acciones de mejora con:
   - prioridad;
   - responsable sugerido;
   - fecha objetivo;
   - indicador objetivo;
   - evidencia de cierre.
7. Crea un informe ejecutivo en Word con:
   - resumen para dirección;
   - tabla de hallazgos por región;
   - riesgos prioritarios;
   - acciones recomendadas;
   - decisiones requeridas.
8. Prepara un borrador de comunicación para la dirección y mensajes específicos
   para las áreas involucradas.

Conserva las cifras del archivo y relaciona cada explicación con su fuente.
Solicita mi aprobación antes de enviar o publicar comunicaciones.
```

2. Sigue el progreso de lectura, análisis y creación del informe.
3. Abre el documento generado.
4. Compara las cifras con el libro de Excel.

![Análisis de indicadores](../images/5.png)

**Resultado Esperado:**

Cowork genera un informe que muestra las variaciones por región, explica su contexto, separa evidencias e hipótesis y propone acciones medibles.


#### Paso 4.3 — Refinar el análisis y preparar decisiones

**Objetivo:** convertir el informe en un elemento útil para la decisión empresarial.

**Instrucciones:**

1. Comprueba que el informe no atribuya automáticamente todas las variaciones a una única causa.
2. Revisa que los riesgos estén priorizados por impacto y urgencia.
3. Comprueba que cada acción se relacione con un indicador.
4. Utiliza el siguiente prompt de refinamiento:

```text
Reorganiza el informe para facilitar la decisión de dirección.

Incluye una tabla final con estas columnas:
- decisión requerida;
- región afectada;
- evidencia principal;
- riesgo de no actuar;
- acción recomendada;
- responsable sugerido;
- fecha límite.

Conserva las cifras originales y señala expresamente cualquier explicación que
continúe siendo una hipótesis.
```

5. Revisa la tabla final.
6. Revisa las comunicaciones propuestas antes de aprobar cualquier acción.

**Resultado Esperado:**

El informe concluye con decisiones concretas y trazables a cifras, riesgos y evidencias.

#### Paso 4.4 — Programar el reporte semanal de indicadores

**Objetivo:** generar un reporte periódico que destaque desviaciones nuevas y decisiones requeridas.

**Instrucciones:**

1. Envía el siguiente prompt:

```text
Programa un reporte semanal todos los viernes a las 15:00.

Revisa la versión más reciente del archivo de indicadores y las fuentes relacionadas.
Genera un reporte que incluya:
- cambios frente a la semana anterior;
- regiones fuera de meta;
- nuevas anomalías;
- causas confirmadas e hipótesis pendientes;
- acciones que necesitan escalamiento;
- tres decisiones recomendadas para la siguiente semana.

Prepara un borrador de comunicación ejecutiva. Solicita mi aprobación antes de
enviarlo y conserva las cifras originales del libro.
```

2. Confirma la frecuencia y la hora.
3. Activa la programación.
4. Ejecuta una primera prueba.
5. Revisa que el reporte se concentre en variaciones nuevas.

![Reporte semanal de indicadores](../images/6.png)

**Resultado Esperado:**

Cowork crea un reporte semanal programado, basado en la versión más reciente del libro y sus fuentes relacionadas.

---

### Parte 5: Cierre y revisión de resultados

**Tiempo estimado:** 5 minutos

#### Paso 5.1 — Revisar tareas, archivos y programaciones

**Objetivo:** confirmar que los tres escenarios quedaron completos y que las acciones programadas pueden administrarse.

**Instrucciones:**

1. Abre la vista **Mis tareas** de Cowork.
2. Confirma que aparecen las tres tareas del taller.
3. Abre cada tarea y revisa su carpeta de salida.
4. Confirma que puedes obtener:
   - el resumen ejecutivo de la reunión;
   - la recomendación de la solicitud estratégica;
   - el informe de indicadores.
5. Abre la sección **Programado**.
6. Confirma que aparecen las tres programaciones creadas.
7. Revisa las acciones que necesitan aprobación.
8. Identifica una decisión, una dependencia y un riesgo que Cowork haya relacionado a través de varias fuentes.

![Revisión de tareas y programaciones](../images/7.png)

**Resultado Esperado:**

Las tres tareas aparecen completas, los archivos generados están disponibles y las programaciones pueden revisarse, pausarse, reanudarse o eliminarse.

---

## Validación y Pruebas

Al finalizar todas las partes, utiliza esta sección para comprobar que los objetivos del taller fueron alcanzados.

### Lista de Verificación Final

| # | Criterio de Validación | Estado |
|---|---|---|
| 1 | Los dos archivos de práctica están almacenados en OneDrive y los siete correos fueron importados en Outlook | ☐ |
| 2 | Cowork analizó la reunión y la conversación relacionada | ☐ |
| 3 | El resumen de reunión contiene decisiones, riesgos y acciones con responsables | ☐ |
| 4 | Se preparó un borrador de correo y una reunión de seguimiento | ☐ |
| 5 | La solicitud estratégica fue consolidada con sus dependencias y fuentes | ☐ |
| 6 | La recomendación distingue hechos, hipótesis e información faltante | ☐ |
| 7 | El plan de trabajo contiene actividades, responsables, fechas, evidencias e hitos | ☐ |
| 8 | Cowork analizó el archivo de indicadores por región y semana | ☐ |
| 9 | Las cifras del informe coinciden con el libro de Excel | ☐ |
| 10 | Las explicaciones están relacionadas con correos, reunión o Teams | ☐ |
| 11 | Las acciones recomendadas contienen indicador objetivo y evidencia de cierre | ☐ |
| 12 | Las tres programaciones fueron creadas y verificadas | ☐ |
| 13 | Las acciones sensibles fueron revisadas antes de aprobarse | ☐ |
| 14 | Los entregables están disponibles en las carpetas de salida | ☐ |

### Criterios de Calidad de los Entregables

| Criterio | Comprobación |
|---|---|
| Trazabilidad | Cada afirmación importante puede relacionarse con una fuente |
| Precisión | Las cifras coinciden con el archivo de Excel |
| Claridad | Los entregables separan hechos, inferencias e información pendiente |
| Accionabilidad | Cada acción tiene responsable, fecha, meta y evidencia |
| Coordinación | Las comunicaciones se adaptan al área o destinatario |
| Control | Las acciones sensibles se revisan antes de aprobarse |
| Seguimiento | Las programaciones destacan cambios desde la ejecución anterior |

### Prueba de Comprensión Conceptual

1. **¿Por qué deben agregarse varias fuentes a una misma tarea?**  
   *Respuesta esperada:* para que Cowork pueda relacionar los datos, los antecedentes, las decisiones y las comunicaciones del mismo caso.

2. **¿Qué información mínima debe tener una acción de seguimiento?**  
   *Respuesta esperada:* actividad, responsable, fecha, dependencia, criterio o evidencia de cierre y fuente.

3. **¿Por qué deben diferenciarse hechos, inferencias e hipótesis?**  
   *Respuesta esperada:* para evitar que una decisión se base en una explicación no confirmada.

4. **¿Qué se debe revisar antes de aprobar un correo, una publicación o una reunión?**  
   *Respuesta esperada:* destinatarios, contenido, fecha, participantes, archivos adjuntos y alcance de la acción.

5. **¿Qué debe destacar una revisión programada?**  
   *Respuesta esperada:* cambios desde la ejecución anterior, riesgos nuevos, acciones vencidas, evidencias agregadas y decisiones pendientes.

---

## Solución de Problemas

### Problema 1: Cowork no aparece en Microsoft 365 Copilot

**Síntoma:** la cuenta puede abrir Microsoft 365 Copilot, pero Cowork no aparece como opción disponible.

**Causa probable:** la cuenta no tiene la licencia requerida, Cowork no está habilitado para el usuario o el tenant no tiene completada la configuración necesaria.

**Solución:**

```text
1. Confirma que has iniciado sesión con la cuenta organizacional correcta.
2. Abre https://m365.cloud.microsoft en una ventana nueva.
3. Revisa que la cuenta tenga una licencia activa de Microsoft 365 Copilot.
4. Solicita al administrador que confirme la disponibilidad de Cowork para el usuario.
5. Cierra sesión, vuelve a iniciar y actualiza la aplicación.
6. Informa al facilitador antes de comenzar los escenarios.
```

### Problema 2: Cowork no encuentra un archivo, una reunión o una cadena de correo

**Síntoma:** Cowork indica que no puede localizar la fuente o genera un resultado sin utilizarla.

**Causa probable:** el nombre no coincide, el archivo no terminó de cargarse, la fuente pertenece a otra cuenta o el usuario no tiene permiso para consultarla.

**Solución:**

```text
1. Abre la fuente directamente desde OneDrive, Teams u Outlook.
2. Confirma el nombre exacto y la cuenta utilizada.
3. Comprueba que tienes permiso para abrirla.
4. En Cowork, elimina la referencia que falló.
5. Vuelve a agregar la fuente desde el botón +.
6. Para los archivos, selecciónalos directamente desde OneDrive o súbelos desde
   el dispositivo.
7. Confirma que aparecen en la carpeta de entrada antes de enviar el prompt.
```

### Problema 3: La tarea permanece sin avanzar

**Síntoma:** el panel de progreso no cambia o Cowork no entrega el resultado.

**Causa probable:** la tarea requiere una aclaración, existe una aprobación pendiente o una fuente no está disponible temporalmente.

**Solución:**

```text
1. Revisa si la tarea aparece como "Necesita tu entrada".
2. Abre la conversación y responde cualquier pregunta pendiente.
3. Revisa las tarjetas de aprobación.
4. Observa el panel de progreso durante al menos 60 segundos.
5. Si no cambia, pausa la tarea y reanúdala.
6. Actualiza la sesión y vuelve a enviar la solicitud cuando sea necesario.
7. Reduce el número de acciones del prompt si el problema se repite.
```

### Problema 4: Una acción no debe ejecutarse

**Síntoma:** Cowork presenta una vista previa de correo, reunión, mensaje o modificación que no coincide con la intención del ejercicio.

**Causa probable:** el prompt contiene un destinatario, una fecha o un alcance ambiguo.

**Solución:**

```text
1. No apruebes la acción.
2. Selecciona Cancelar en la tarjeta correspondiente.
3. Indica a Cowork el elemento que debe corregir.
4. Solicita una nueva vista previa.
5. Revisa destinatarios, fechas, participantes, contenido y adjuntos.
6. Aprueba únicamente cuando todos los detalles sean correctos.
```

### Problema 5: La revisión programada no aparece o no se ejecuta

**Síntoma:** el prompt fue aceptado, pero no aparece en la sección Programado.

**Causa probable:** la programación quedó como borrador, la frecuencia no fue interpretada o no se confirmó su activación.

**Solución:**

```text
1. Abre Programado en la navegación de Cowork.
2. Entra en Administrar programaciones.
3. Busca la solicitud creada durante el escenario.
4. Revisa hora, frecuencia, fecha final y fuentes.
5. Activa la programación.
6. Selecciona Activar y ejecutar ahora para realizar una prueba.
7. Revisa la ejecución y corrige el prompt cuando el resultado no tenga el
   formato esperado.
```

---

## Limpieza del Entorno

Una vez finalizado el taller, limpia los elementos generados para evitar acciones futuras o acumulación de datos de práctica.

**Tiempo estimado:** 5 minutos fuera del tiempo de instrucción.

### Pasos de Limpieza

#### 1. Pausar o eliminar las programaciones

```text
1. Abre Cowork.
2. Selecciona Programado.
3. Entra en Administrar programaciones.
4. Localiza las tres programaciones del taller.
5. Pausa o elimina:
   - revisión semanal de la reunión;
   - revisión diaria de la solicitud estratégica;
   - reporte semanal de indicadores.
6. Confirma que ninguna programación de práctica permanece activa.
```

#### 2. Revisar comunicaciones y reuniones

```text
1. Abre Outlook.
2. Revisa la carpeta Borradores y elimina los mensajes de práctica que no se utilizarán.
3. Revisa Elementos enviados si se aprobó algún envío durante la demostración.
4. Abre el calendario y elimina la reunión de seguimiento creada para el caso.
5. Abre Teams y elimina los mensajes de práctica cuando las políticas del tenant
   y los permisos lo permitan.
```

#### 3. Eliminar archivos generados

```text
1. Abre las tareas completadas en Cowork.
2. Revisa la carpeta de salida de cada tarea.
3. Conserva únicamente los entregables requeridos por el facilitador.
4. En OneDrive, elimina los documentos generados que no deban permanecer.
5. Vacía la papelera únicamente cuando estés seguro de que los archivos son de práctica.
```

#### 4. Archivar los materiales del taller

```text
1. Abre OneDrive.
2. Navega a Taller-Cowork-Expansion.
3. Conserva los dos archivos originales y la carpeta de correos `.eml` cuando quieras repetir la práctica.
4. Mueve la carpeta a una ubicación de archivo o elimínala cuando ya no sea necesaria.
```

---

## Resumen

### Lo que Aprendiste en este Laboratorio

En este taller de 70 minutos utilizaste Copilot Cowork para transformar información distribuida en Microsoft 365 en entregables y acciones coordinadas. La reunión permitió identificar decisiones y compromisos; la cadena de correo permitió consolidar dependencias y preparar una recomendación; el archivo de Excel permitió detectar desviaciones y explicar su contexto mediante fuentes relacionadas.

| Concepto | Aplicación en el Laboratorio |
|---|---|
| **Trabajo de varios pasos** | Cowork analizó fuentes, creó documentos y preparó acciones dentro de una misma tarea |
| **Contexto de Microsoft 365** | Se utilizaron reuniones, Teams, Outlook, OneDrive y Excel |
| **Trazabilidad** | Los hallazgos y recomendaciones se relacionaron con sus fuentes |
| **Aprobación de acciones** | Se revisaron correos, mensajes y reuniones antes de ejecutarlos |
| **Análisis contextual** | Las cifras del Excel se explicaron con información de reuniones y correos |
| **Seguimiento programado** | Se configuraron revisiones periódicas para detectar cambios y riesgos |

### Principios de Delegación Efectiva Consolidados

1. **Define el objetivo empresarial:** indica qué decisión o resultado debe apoyar la tarea.
2. **Agrega fuentes específicas:** incorpora únicamente reuniones, correos, conversaciones y archivos relacionados.
3. **Describe las acciones:** enumera los pasos y los entregables esperados.
4. **Exige evidencia:** solicita la fuente que respalda cada afirmación relevante.
5. **Separa hechos e hipótesis:** marca la información pendiente de confirmación.
6. **Establece criterios de calidad:** define formato, extensión, fechas, indicadores y criterios de cierre.
7. **Revisa antes de aprobar:** comprueba destinatarios, contenido, fechas, participantes y permisos.
8. **Programa el seguimiento:** define frecuencia, fuentes, cambios que deben detectarse y forma de comunicar el resultado.

### Próximos Pasos

Repite el flujo con un caso de prueba propio que utilice información no sensible. Mantén la misma secuencia: agregar fuentes, definir el resultado, revisar el plan, validar evidencias, aprobar acciones y configurar seguimiento.

### Recursos Adicionales

| Recurso | Descripción |
|---|---|
| [Introducción a Copilot Cowork](https://learn.microsoft.com/es-es/microsoft-365/copilot/cowork/) | Capacidades, acciones disponibles y administración del trabajo |
| [Introducción y requisitos de Cowork](https://learn.microsoft.com/es-es/microsoft-365/copilot/cowork/get-started) | Licencia, habilitación, facturación basada en uso y primeros pasos |
| [Uso de Copilot Cowork](https://learn.microsoft.com/es-es/microsoft-365/copilot/cowork/use-cowork) | Sesiones, archivos, panel lateral, aprobaciones, tareas y programaciones |
| [Importación masiva de archivos EML](https://support.microsoft.com/es-es/office/importar-eml-archivos-en-masa-en-el-nuevo-outlook-0ec85d73-fb14-41f6-8b8e-0e7647fa7db1) | Procedimiento oficial para importar los correos del taller en el nuevo Outlook |

---

*Laboratorio desarrollado para el Módulo 2 del curso de Microsoft 365 Copilot Cowork. Versión 1.0.*
