# Taller práctico. El verdadero potencial de Copilot Cowork

## Metadatos

| Campo            | Detalle                                      |
|------------------|----------------------------------------------|
| **Duración**     | 70 minutos                                   |
| **Complejidad**  | Media                                        |
| **Nivel Bloom**  | Aplicar (Apply)                              |
| **Módulo**       | 1.0 — Fundamentos de Copilot Cowork          |
| **Versión**      | 1.0                                          |

---

## Descripción General

En este taller práctico los participantes explorarán de primera mano la diferencia fundamental entre Copilot Chat y Copilot Cowork: mientras el primero genera contenido bajo demanda, el segundo **actúa como un agente de ejecución** capaz de completar tareas complejas y multietapa de forma autónoma dentro del ecosistema Microsoft 365. A través de tres casos de uso empresariales de alto impacto —análisis de datos en Excel, gestión de correos en Outlook y planificación de proyectos en Planner— los participantes experimentarán directamente el modelo de delegación inteligente de trabajo que define a Copilot Cowork. El taller cierra con una sesión de reflexión estructurada para consolidar buenas prácticas personales de delegación.

> ⚠️ **Aviso de privacidad:** Durante todo el laboratorio, utiliza **exclusivamente los archivos de práctica proporcionados por el facilitador**. No ingreses datos reales, confidenciales o sensibles de tu organización en ninguna instrucción o prompt de Copilot.

---

## Objetivos de Aprendizaje

Al finalizar este laboratorio serás capaz de:

- [ ] Distinguir conceptualmente y en la práctica las diferencias entre Copilot Chat y Copilot Cowork, identificando el tipo de tarea adecuado para cada herramienta.
- [ ] Aplicar el modelo de delegación de trabajo complejo utilizando Copilot Cowork para ejecutar al menos tres tareas empresariales de alto impacto dentro del ecosistema Microsoft 365.
- [ ] Construir instrucciones estructuradas (prompts de delegación) siguiendo las buenas prácticas para asignar trabajo complejo a Copilot Cowork de manera efectiva.
- [ ] Evaluar los resultados generados por Copilot Cowork comparándolos con outputs de Copilot Chat, identificando ventajas, limitaciones y casos de uso óptimos para cada herramienta.

---

## Prerrequisitos

### Conocimientos Previos

| Área                       | Nivel Requerido                                                                                   |
|----------------------------|---------------------------------------------------------------------------------------------------|
| Microsoft Teams            | Básico — navegación por canales, chats y pestañas de aplicaciones                                |
| Microsoft Outlook          | Básico — lectura, redacción y organización de correos electrónicos                               |
| Microsoft Excel            | Básico — apertura de archivos, navegación entre hojas, comprensión de tablas de datos            |
| Microsoft Planner          | Básico — acceso a planes existentes o permisos para crear uno nuevo                              |
| Conceptos del Módulo 1.0   | Haber revisado la Lección 1.1 o participado en la sesión introductoria del curso                 |

### Acceso y Licencias Requeridas

| Recurso                                      | Estado Requerido                                                    |
|----------------------------------------------|---------------------------------------------------------------------|
| Licencia Microsoft 365 Copilot con Cowork    | ✅ Activa y verificada al menos 24 horas antes del laboratorio       |
| Microsoft Teams (versión más reciente)       | ✅ Instalado y con sesión iniciada en el tenant corporativo          |
| Microsoft Outlook (M365 Apps)                | ✅ Configurado con cuenta organizacional                             |
| Microsoft Excel (M365 Apps)                  | ✅ Instalado con acceso a OneDrive/SharePoint del tenant             |
| Microsoft Planner                            | ✅ Accesible vía web o integración en Teams                          |
| Archivos de práctica del facilitador         | ✅ Descargados en OneDrive antes de iniciar el laboratorio           |

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

| Aplicación                  | Versión Mínima                            |
|-----------------------------|-------------------------------------------|
| Microsoft Teams             | Canal actual (versión más reciente)       |
| Microsoft Outlook           | M365 Apps (versión más reciente)          |
| Microsoft Excel             | M365 Apps (versión más reciente)          |
| Microsoft Planner           | Versión web o integración en Teams        |
| Microsoft Edge / Chrome     | Edge 120+ / Chrome 120+                   |

### Preparación del Entorno Antes de Comenzar

Realiza los siguientes pasos de configuración **antes** de iniciar los ejercicios. Tiempo estimado: 5 minutos.

**1. Verificar acceso a Copilot Cowork en Teams:**

```
1. Abre Microsoft Teams.
2. En la barra lateral izquierda, busca el ícono de Copilot (icono de chispa/estrella).
3. Haz clic en él y verifica que aparezca la opción "Cowork" o una interfaz de agente 
   diferenciada del chat estándar de Copilot.
4. Si no aparece la opción Cowork, notifica al facilitador antes de continuar.
```

**2. Cargar los archivos de práctica en OneDrive:**

```
1. Abre un navegador y accede a: https://onedrive.live.com (cuenta organizacional)
2. Crea una carpeta llamada: Lab-Cowork-Practica
3. Sube los tres archivos proporcionados por el facilitador:
   - ventas_ficticias_Q3.xlsx
   - correos_practica_template.oft (o el formato indicado por el facilitador)
   - descripcion_proyecto_ficticio.docx
4. Confirma que los tres archivos son visibles en la carpeta antes de continuar.
```

**3. Abrir aplicaciones necesarias en paralelo:**

```
Abre y mantén activas las siguientes aplicaciones (minimizadas si es necesario):
- Microsoft Teams
- Microsoft Outlook
- Microsoft Excel
- Microsoft Edge con Planner: https://tasks.office.com
```

---

## Instrucciones Paso a Paso

---

### Parte 1: Exploración de la Interfaz — Copilot Chat vs. Copilot Cowork

**Tiempo estimado:** 15 minutos

---

#### Paso 1.1 — Acceder a Copilot Chat y registrar sus características

**Objetivo:** Familiarizarse con la interfaz de Copilot Chat como punto de referencia para la comparación posterior.

**Instrucciones:**

1. En Microsoft Teams, haz clic en el ícono de **Copilot** en la barra lateral izquierda.
2. Verifica que estás en la vista de **Copilot Chat** (interfaz conversacional estándar).
3. En el cuadro de texto, escribe exactamente el siguiente prompt y presiona **Enter**:

```
Resume brevemente qué hace un gerente de proyectos en una empresa de tecnología.
```

4. Observa y anota en tu cuaderno o en un documento de texto:
   - ¿Qué tipo de respuesta recibiste? (texto, lista, párrafo)
   - ¿Cuántos pasos realizó Copilot para responder?
   - ¿Accedió a alguna aplicación o dato de tu organización?
   - ¿Cuánto tiempo tardó en responder?

5. Escribe un segundo prompt para explorar los límites de Copilot Chat:

```
Revisa mis correos de la última semana en Outlook, identifica los tres temas 
más urgentes y redacta un resumen ejecutivo para mi jefe.
```

6. Anota la respuesta: ¿Copilot Chat ejecutó la tarea o simplemente ofreció orientación general?

**Resultado Esperado:**

Copilot Chat responderá el primer prompt con texto generado de forma inmediata y correcta. Para el segundo prompt, es probable que ofrezca una respuesta genérica, indique que no puede acceder directamente a tu Outlook, o solicite que copies y pegues el contenido manualmente. Esto ilustra su naturaleza de **asistente de generación de contenido**, no de agente de ejecución.

**Verificación:**

- [ ] Recibiste una respuesta de texto al primer prompt en menos de 15 segundos.
- [ ] Pudiste identificar que Copilot Chat **no ejecutó** la tarea multiaplicación del segundo prompt de forma autónoma.
- [ ] Tienes anotadas al menos 3 observaciones sobre las características de Copilot Chat.

---

#### Paso 1.2 — Acceder a Copilot Cowork y explorar su interfaz diferenciada

**Objetivo:** Identificar los elementos visuales y funcionales que distinguen a Copilot Cowork de Copilot Chat.

**Instrucciones:**

1. Dentro de Microsoft Teams, busca la sección de **Copilot** y localiza la opción para acceder a **Copilot Cowork** (puede aparecer como una pestaña separada, un agente específico o una opción en el menú de Copilot según la versión de tu tenant).

   > 💡 **Nota:** En algunos tenants, Copilot Cowork aparece como una aplicación separada en la barra lateral de Teams o como una opción dentro del menú de Copilot bajo el nombre "Agentes" o "Cowork". Si tienes dudas sobre dónde encontrarlo, consulta al facilitador antes de continuar.

2. Una vez en la interfaz de Copilot Cowork, observa y documenta las diferencias visuales respecto a Copilot Chat:
   - ¿Hay indicadores de "estado" o "progreso" en la interfaz?
   - ¿Aparecen referencias a aplicaciones conectadas (Teams, Outlook, Planner, etc.)?
   - ¿Existe alguna opción para ver los "pasos" o "acciones" que Cowork ejecutará?

3. Escribe el mismo segundo prompt que usaste en el Paso 1.1:

```
Revisa mis correos de la última semana en Outlook, identifica los tres temas 
más urgentes y redacta un resumen ejecutivo para mi jefe.
```

4. Observa el comportamiento de Cowork:
   - ¿Solicita confirmación antes de acceder a Outlook?
   - ¿Muestra pasos intermedios de ejecución?
   - ¿El resultado final es diferente al de Copilot Chat?

5. Completa la siguiente tabla comparativa en tu documento de notas:

```
| Criterio                          | Copilot Chat | Copilot Cowork |
|-----------------------------------|--------------|----------------|
| Accede a aplicaciones M365        |              |                |
| Muestra pasos de ejecución        |              |                |
| Requiere instrucciones paso a paso|              |                |
| Entrega resultado ejecutable      |              |                |
| Tiempo de respuesta               |              |                |
```

**Resultado Esperado:**

Copilot Cowork debería iniciar un proceso de ejecución visible: acceder a Outlook, procesar los correos disponibles, identificar los temas urgentes y generar un resumen estructurado. La interfaz mostrará indicadores de progreso o pasos intermedios, lo que contrasta directamente con la respuesta estática de Copilot Chat.

**Verificación:**

- [ ] Identificaste al menos 3 diferencias visuales entre las interfaces de Copilot Chat y Copilot Cowork.
- [ ] Copilot Cowork inició un proceso de ejecución multietapa (no solo generó texto).
- [ ] Completaste la tabla comparativa con observaciones propias.

---

### Parte 2: Ejercicio Comparativo Directo — Delegación vs. Generación

**Tiempo estimado:** 10 minutos

---

#### Paso 2.1 — Ejecutar el ejercicio comparativo con una tarea de análisis

**Objetivo:** Experimentar de forma directa y documentada la diferencia entre generar contenido y delegar trabajo, usando la misma tarea en ambas herramientas.

**Instrucciones:**

1. Abre el archivo **ventas_ficticias_Q3.xlsx** desde tu carpeta `Lab-Cowork-Practica` en OneDrive.

2. **Primero, en Copilot Chat:** Escribe el siguiente prompt:

```
Analiza los datos de ventas del tercer trimestre que tengo en Excel y dime 
cuáles son los tres productos con mayor crecimiento respecto al trimestre anterior.
```

3. Anota el resultado: ¿Copilot Chat pudo acceder al archivo? ¿Qué respuesta generó?

4. **Ahora, en Copilot Cowork:** Escribe el siguiente prompt de delegación estructurado:

```
Tarea: Analizar el rendimiento de ventas del Q3.

Contexto: Tengo un archivo llamado "ventas_ficticias_Q3.xlsx" guardado en mi 
OneDrive en la carpeta "Lab-Cowork-Practica". Contiene datos de ventas por 
producto para Q2 y Q3 del año en curso.

Acción requerida:
1. Abre el archivo y revisa los datos de ventas por producto.
2. Calcula el porcentaje de crecimiento de Q2 a Q3 para cada producto.
3. Identifica los tres productos con mayor crecimiento.
4. Genera un resumen ejecutivo de 3 párrafos con los hallazgos principales, 
   incluyendo una tabla comparativa.

Entregable: Resumen ejecutivo listo para presentar a un directivo.
```

5. Observa el proceso de ejecución de Cowork y anota:
   - ¿Accedió al archivo de OneDrive?
   - ¿Mostró pasos intermedios?
   - ¿El resultado fue más completo y ejecutable que el de Copilot Chat?

**Resultado Esperado:**

Copilot Chat ofrecerá orientación general sobre cómo analizar datos o solicitará que pegues los datos manualmente. Copilot Cowork accederá al archivo, procesará los datos y entregará un resumen ejecutivo estructurado con la tabla comparativa solicitada, listo para ser utilizado directamente.

**Verificación:**

- [ ] Ejecutaste el mismo ejercicio en ambas herramientas y documentaste las diferencias.
- [ ] Copilot Cowork accedió al archivo de OneDrive sin que copiaras y pegaras los datos manualmente.
- [ ] El resultado de Cowork incluye un resumen ejecutivo estructurado con tabla comparativa.

---

### Parte 3: Caso de Uso 1 — Delegación de Análisis en Excel

**Tiempo estimado:** 12 minutos

---

#### Paso 3.1 — Construir y ejecutar un prompt de delegación avanzado para Excel

**Objetivo:** Aplicar las buenas prácticas de construcción de prompts de delegación para obtener un análisis ejecutivo completo desde datos de Excel.

**Instrucciones:**

1. Asegúrate de que el archivo **ventas_ficticias_Q3.xlsx** sigue abierto en Excel y accesible desde OneDrive.

2. En Copilot Cowork, escribe el siguiente prompt de delegación estructurado. Observa cómo está construido: incluye **contexto**, **objetivo claro**, **pasos específicos** y **formato de entregable**:

```
Contexto: Soy gerente comercial y necesito presentar el desempeño de ventas 
del Q3 a la dirección general en una reunión mañana.

Archivo de trabajo: "ventas_ficticias_Q3.xlsx" en mi OneDrive, 
carpeta "Lab-Cowork-Practica".

Objetivo: Preparar un análisis ejecutivo completo del desempeño de ventas Q3.

Tareas a ejecutar:
1. Revisa todos los datos del archivo (ventas por producto, región y mes).
2. Identifica las 3 métricas de mayor importancia para una presentación directiva.
3. Detecta cualquier anomalía o tendencia relevante en los datos.
4. Redacta un informe ejecutivo con: 
   - Párrafo de resumen (máximo 100 palabras)
   - Tabla de top 5 productos por volumen de ventas en Q3
   - Sección de "Puntos de atención" con máximo 3 alertas
   - Recomendación de acción para el Q4

Formato de entrega: Documento Word estructurado con título, fecha de hoy 
y secciones claramente delimitadas.

Restricción: Usa solo los datos del archivo proporcionado. No inventes cifras.
```

3. Mientras Cowork ejecuta la tarea, observa y documenta en tiempo real:
   - Los pasos intermedios que aparecen en la interfaz.
   - Cualquier solicitud de confirmación o aclaración que haga Cowork.
   - El tiempo total de ejecución.

4. Cuando recibas el resultado, evalúalo con los siguientes criterios:

```
Criterios de evaluación del resultado:
[ ] ¿El informe tiene todas las secciones solicitadas?
[ ] ¿Los datos citados corresponden al archivo de práctica?
[ ] ¿El resumen tiene 100 palabras o menos?
[ ] ¿La tabla de top 5 productos está correctamente formateada?
[ ] ¿Las recomendaciones son coherentes con los datos presentados?
```

5. Si algún criterio no se cumple, redacta un **prompt de refinamiento** para corregirlo. Ejemplo:

```
El informe está bien estructurado, pero la sección de "Puntos de atención" 
solo tiene 2 alertas. Por favor, agrega una tercera alerta relacionada con 
la variación de ventas por región. Mantén el resto del documento igual.
```

**Resultado Esperado:**

Copilot Cowork generará un documento Word estructurado con todas las secciones solicitadas, basado en los datos del archivo de práctica. El proceso mostrará pasos intermedios visibles (lectura del archivo, análisis de datos, generación de secciones). El documento final debería estar listo para presentar con mínimas modificaciones.

**Verificación:**

- [ ] El documento generado contiene las 4 secciones solicitadas en el prompt.
- [ ] Los datos del informe corresponden al archivo ventas_ficticias_Q3.xlsx.
- [ ] Identificaste al menos un aspecto del resultado que podrías refinar con un prompt adicional.
- [ ] Completaste los criterios de evaluación del resultado.

---

### Parte 4: Caso de Uso 2 — Gestión Inteligente de Correos en Outlook

**Tiempo estimado:** 12 minutos

---

#### Paso 4.1 — Delegar la priorización y respuesta de correos a Copilot Cowork

**Objetivo:** Utilizar Copilot Cowork para gestionar una cadena de correos de forma inteligente, incluyendo priorización y redacción de respuestas múltiples.

**Instrucciones:**

1. Abre Microsoft Outlook y accede a la carpeta de práctica preparada por el facilitador (o a tu bandeja de entrada si el facilitador indicó usar correos reales no sensibles).

   > ⚠️ **Recordatorio crítico:** Si usas tu bandeja de entrada real, asegúrate de que los correos seleccionados **no contengan información confidencial, datos personales sensibles o información estratégica de la organización**.

2. Identifica visualmente la carpeta o los correos de práctica. Toma nota del nombre exacto de la carpeta o de los remitentes/asuntos de los correos de práctica.

3. En Copilot Cowork, escribe el siguiente prompt de delegación:

```
Contexto: Soy directora de operaciones y acabo de regresar de 3 días de 
viaje. Tengo correos pendientes en Outlook que necesito gestionar 
eficientemente.

Carpeta de trabajo: [Nombre de la carpeta de práctica indicada por el facilitador]

Tareas a ejecutar:
1. Revisa todos los correos no leídos en la carpeta indicada.
2. Clasifícalos en tres categorías: URGENTE, PENDIENTE y PARA INFORMACIÓN.
3. Para los correos clasificados como URGENTE: redacta una respuesta profesional 
   y cordial que acuse recibo e indique que daré respuesta detallada antes de 
   las 5pm de hoy.
4. Para los correos clasificados como PENDIENTE: redacta un resumen de una línea 
   con la acción requerida de mi parte.
5. Genera un reporte de bandeja de entrada con las tres categorías y los correos 
   correspondientes.

Formato de entrega: 
- Borradores de respuesta listos en Outlook (no envíes, solo guarda como borrador)
- Reporte de clasificación en texto estructurado dentro de este chat

Restricción importante: NO envíes ningún correo. Solo guarda borradores.
```

4. Observa el proceso de ejecución. Presta especial atención a:
   - ¿Cowork solicita confirmación antes de crear borradores en Outlook?
   - ¿Los borradores creados aparecen en la carpeta "Borradores" de Outlook?
   - ¿La clasificación de correos es coherente con el contenido de los mensajes?

5. Ve a Outlook y verifica la carpeta **Borradores** para confirmar que los borradores fueron creados correctamente.

6. Abre uno de los borradores y evalúa:
   - ¿El tono es profesional y apropiado?
   - ¿El mensaje cumple con lo solicitado (acuse de recibo + compromiso de respuesta)?
   - ¿Necesita algún ajuste antes de enviarse?

**Resultado Esperado:**

Copilot Cowork accederá a la carpeta de Outlook indicada, clasificará los correos en las tres categorías, creará borradores de respuesta para los correos urgentes y generará el reporte de clasificación. Los borradores deberían aparecer en la carpeta "Borradores" de Outlook con el asunto y destinatario correctos.

**Verificación:**

- [ ] Copilot Cowork accedió a Outlook sin que proporcionaras el contenido de los correos manualmente.
- [ ] Aparecen borradores nuevos en la carpeta "Borradores" de Outlook.
- [ ] El reporte de clasificación muestra las tres categorías con los correos correspondientes.
- [ ] Los borradores tienen un tono profesional y cumplen con el objetivo del prompt.
- [ ] Confirmaste que ningún correo fue enviado (solo guardado como borrador).

---

### Parte 5: Caso de Uso 3 — Planificación de Proyectos en Planner

**Tiempo estimado:** 12 minutos

---

#### Paso 5.1 — Crear un plan de proyecto completo en Planner desde una descripción de objetivos

**Objetivo:** Delegar a Copilot Cowork la creación estructurada de un plan de proyecto en Microsoft Planner a partir de una descripción de objetivos de negocio en lenguaje natural.

**Instrucciones:**

1. Abre el archivo **descripcion_proyecto_ficticio.docx** desde tu carpeta `Lab-Cowork-Practica` en OneDrive. Lee el contenido para familiarizarte con el proyecto ficticio (no más de 2 minutos).

2. Accede a Microsoft Planner en tu navegador: `https://tasks.office.com`

3. Verifica que tienes permisos para crear un nuevo plan. Si no los tienes, notifica al facilitador.

4. En Copilot Cowork, escribe el siguiente prompt de delegación:

```
Contexto: Soy gerente de transformación digital y necesito estructurar un 
nuevo proyecto para mi equipo. El proyecto está descrito en el archivo 
"descripcion_proyecto_ficticio.docx" en mi OneDrive, carpeta "Lab-Cowork-Practica".

Objetivo: Crear un plan de proyecto completo y funcional en Microsoft Planner.

Tareas a ejecutar:
1. Lee el archivo de descripción del proyecto.
2. Identifica los objetivos principales, entregables y restricciones mencionados.
3. Crea un nuevo plan en Microsoft Planner con el nombre del proyecto indicado 
   en el archivo.
4. Estructura el plan con los siguientes cubos (buckets):
   - Fase 1: Diagnóstico y Planificación
   - Fase 2: Desarrollo y Ejecución  
   - Fase 3: Validación y Cierre
5. Crea al menos 3 tareas por cubo, basadas en los entregables del proyecto.
6. Para cada tarea incluye: título descriptivo, fecha de vencimiento estimada 
   (distribuidas en 12 semanas desde hoy) y etiqueta de prioridad (Alta/Media/Baja).
7. Agrega una nota en la descripción del plan con el resumen ejecutivo del proyecto 
   (máximo 5 líneas).

Entregable: Plan funcional creado en Planner con todas las tareas configuradas.

Restricción: Usa solo la información del archivo. No inventes objetivos o 
entregables que no estén en el documento.
```

5. Mientras Cowork ejecuta la tarea, observa:
   - ¿Muestra los pasos de lectura del archivo, análisis y creación en Planner?
   - ¿Solicita confirmación antes de crear el plan?

6. Una vez completada la ejecución, abre Microsoft Planner y verifica el nuevo plan:
   - ¿Aparecen los tres cubos (buckets) solicitados?
   - ¿Cada cubo tiene al menos 3 tareas?
   - ¿Las tareas tienen fechas de vencimiento y etiquetas de prioridad?

7. Haz clic en una tarea y verifica que tiene título, fecha y prioridad correctamente configurados.

**Resultado Esperado:**

Copilot Cowork leerá el archivo de descripción del proyecto, estructurará un plan coherente con los objetivos identificados y creará el plan completo en Microsoft Planner con los tres cubos y las tareas correspondientes. El plan debería ser funcional e inmediatamente utilizable por un equipo real.

**Verificación:**

- [ ] Aparece un nuevo plan en Microsoft Planner con el nombre del proyecto ficticio.
- [ ] El plan tiene exactamente 3 cubos (Fase 1, Fase 2, Fase 3).
- [ ] Cada cubo tiene al menos 3 tareas con título, fecha de vencimiento y prioridad.
- [ ] La descripción del plan contiene el resumen ejecutivo del proyecto.
- [ ] Las tareas están basadas en el contenido del archivo de descripción (no inventadas).

---

### Parte 6: Reflexión Estructurada y Documentación de Buenas Prácticas

**Tiempo estimado:** 9 minutos

---

#### Paso 6.1 — Construir tu guía personal de delegación efectiva

**Objetivo:** Consolidar el aprendizaje del taller documentando buenas prácticas propias de delegación a Copilot Cowork, basadas en los resultados obtenidos en los tres casos de uso.

**Instrucciones:**

1. Abre un documento de Word nuevo (puedes pedirle a Copilot Cowork que lo cree por ti como ejercicio adicional).

2. Titula el documento: **"Mi Guía Personal de Delegación con Copilot Cowork — [Tu nombre] — [Fecha]"**

3. Basándote en tu experiencia en los Pasos 3.1, 4.1 y 5.1, responde las siguientes preguntas y escríbelas en el documento:

```
SECCIÓN 1: Anatomía de un buen prompt de delegación
Pregunta: ¿Qué elementos estuvieron presentes en los prompts que generaron 
los mejores resultados? Lista al menos 5 componentes con una descripción breve.

SECCIÓN 2: Cuándo usar Copilot Chat vs. Copilot Cowork
Pregunta: Basándote en lo que observaste hoy, completa esta tabla:

| Tipo de tarea                          | Herramienta ideal | Por qué          |
|----------------------------------------|-------------------|------------------|
| Generar un texto de presentación       |                   |                  |
| Analizar datos de múltiples archivos   |                   |                  |
| Responder una pregunta rápida          |                   |                  |
| Crear un plan de proyecto completo     |                   |                  |
| Resumir el contenido de un documento   |                   |                  |
| Gestionar bandeja de entrada de correos|                   |                  |

SECCIÓN 3: Mis 3 reglas personales de delegación efectiva
Pregunta: ¿Qué tres principios aplicarás en tu trabajo diario al delegar 
tareas a Copilot Cowork? Escríbelos como reglas accionables.

SECCIÓN 4: Limitaciones identificadas
Pregunta: ¿En qué momentos Copilot Cowork no cumplió exactamente con lo 
esperado? ¿Cómo podrías mejorar el prompt para obtener un mejor resultado?
```

4. Comparte tu documento con el facilitador o con un compañero para recibir retroalimentación (opcional según instrucciones del facilitador).

5. Guarda el documento en tu carpeta `Lab-Cowork-Practica` en OneDrive con el nombre:
   `GuiaDelegacion_[TuNombre]_Lab01.docx`

**Resultado Esperado:**

Un documento personal de referencia con al menos 4 secciones completadas, que refleje observaciones reales del taller. Este documento servirá como guía práctica para el uso de Copilot Cowork en el contexto laboral real del participante.

**Verificación:**

- [ ] El documento tiene las 4 secciones con respuestas basadas en la experiencia del taller.
- [ ] La tabla de la Sección 2 está completada con criterios propios.
- [ ] Las 3 reglas de la Sección 3 son accionables y específicas (no genéricas).
- [ ] El documento está guardado en OneDrive con el nombre correcto.

---

## Validación y Pruebas

Al finalizar todas las partes del laboratorio, realiza la siguiente verificación integral para confirmar que los objetivos de aprendizaje fueron alcanzados.

### Lista de Verificación Final

| # | Criterio de Validación                                                                                      | Estado |
|---|-------------------------------------------------------------------------------------------------------------|--------|
| 1 | Puedes explicar en una oración la diferencia fundamental entre Copilot Chat y Copilot Cowork                | ☐      |
| 2 | Completaste la tabla comparativa del Paso 1.2 con observaciones propias y específicas                       | ☐      |
| 3 | El ejercicio comparativo del Paso 2.1 mostró una diferencia clara en el tipo de resultado de cada herramienta| ☐      |
| 4 | Copilot Cowork generó un informe ejecutivo de Excel con las 4 secciones solicitadas                         | ☐      |
| 5 | Aparecen borradores de correo en Outlook creados por Copilot Cowork (sin correos enviados)                  | ☐      |
| 6 | Existe un plan funcional en Microsoft Planner con 3 cubos y al menos 9 tareas totales                       | ☐      |
| 7 | Tu guía personal de delegación está guardada en OneDrive con las 4 secciones completadas                    | ☐      |
| 8 | Puedes identificar al menos 2 tipos de tareas donde Copilot Chat es más adecuado que Cowork                 | ☐      |

### Prueba de Comprensión Conceptual

Responde mentalmente (o por escrito si el facilitador lo solicita) las siguientes preguntas:

1. **¿Cuáles son los tres pilares técnicos que hacen posible el funcionamiento de Copilot Cowork?** *(Respuesta esperada: Modelo de lenguaje LLM, Orquestación de agentes, Conectores de Microsoft Graph)*

2. **¿Por qué Copilot Cowork puede ejecutar tareas en Outlook o Planner sin que el usuario copie y pegue información manualmente?** *(Respuesta esperada: Porque utiliza los conectores de Microsoft Graph para acceder a los datos organizacionales dentro del perímetro de seguridad del tenant)*

3. **¿Qué elemento de un prompt de delegación es más crítico para obtener un resultado de calidad con Copilot Cowork?** *(Respuesta esperada: El contexto claro + el entregable específico; las respuestas pueden variar pero deben mencionar la especificidad del objetivo y el formato del resultado)*

---

## Solución de Problemas

### Problema 1: Copilot Cowork no aparece en la interfaz de Teams

**Síntoma:** Al acceder a la sección de Copilot en Teams, solo aparece la interfaz de Copilot Chat estándar. No hay opción visible de "Cowork", "Agentes" o una interfaz diferenciada para delegación de trabajo.

**Causa probable:** La licencia de Microsoft 365 Copilot con Cowork no está activa en el tenant, la funcionalidad está en rollout gradual para la región geográfica del tenant, o la activación de la licencia aún no se ha propagado (puede tardar hasta 24 horas).

**Solución:**

```
Paso 1: Verifica el estado de tu licencia
- Accede a: https://portal.office.com
- Ve a "Mi cuenta" > "Suscripciones" o "Licencias"
- Confirma que aparece "Microsoft 365 Copilot" como licencia activa

Paso 2: Verifica la disponibilidad en tu tenant
- Solicita al administrador de TI que confirme si Copilot Cowork 
  está habilitado en el tenant de la organización
- URL de administración: https://admin.microsoft.com

Paso 3: Alternativa inmediata para el laboratorio
- Notifica al facilitador
- El facilitador activará el modo de demostración en pantalla compartida
- Completa los ejercicios observando la demostración y documentando 
  los resultados mostrados como si fueran propios
- Puedes completar el Paso 6.1 (guía personal) basándote en la demostración
```

> 📌 **Nota para el facilitador:** Tener preparada la demostración en pantalla compartida como alternativa es crítico. Asegúrate de tener acceso a un tenant con Cowork activo para esta contingencia.

---

### Problema 2: Copilot Cowork no puede acceder al archivo de OneDrive o a los correos de Outlook

**Síntoma:** Al ejecutar los prompts de los Pasos 3.1, 4.1 o 5.1, Copilot Cowork responde que no puede encontrar el archivo, que no tiene acceso a la carpeta indicada, o que no puede leer los correos de Outlook. El proceso se detiene o genera un resultado basado en información inventada.

**Causa probable:** El archivo no está correctamente cargado en OneDrive, el nombre del archivo en el prompt no coincide exactamente con el nombre real del archivo, los permisos de acceso de Cowork no están configurados para acceder a OneDrive o Outlook del usuario, o la carpeta tiene un nombre diferente al indicado en el prompt.

**Solución:**

```
Paso 1: Verifica la ubicación y nombre exacto del archivo
- Abre OneDrive en el navegador: https://onedrive.live.com
- Navega a la carpeta "Lab-Cowork-Practica"
- Confirma el nombre EXACTO del archivo (mayúsculas, espacios, extensión)
- Ejemplo: "ventas_ficticias_Q3.xlsx" ≠ "Ventas Ficticias Q3.xlsx"

Paso 2: Corrige el prompt con el nombre exacto
- Modifica el prompt usando el nombre exacto del archivo
- Incluye la ruta completa si es necesario:
  "OneDrive > Lab-Cowork-Practica > ventas_ficticias_Q3.xlsx"

Paso 3: Verifica los permisos de Copilot Cowork
- En Teams, accede a la configuración de Copilot
- Confirma que Cowork tiene permisos para acceder a OneDrive y Outlook
- Si los permisos no están habilitados, solicita al administrador de TI 
  que revise la configuración de Microsoft Graph en el tenant

Paso 4: Alternativa si el problema persiste
- Para el caso de Excel: Abre el archivo en Excel, selecciona todos los datos 
  (Ctrl+A), cópialos y pégalos directamente en el prompt de Cowork como texto
- Para el caso de Outlook: Copia el texto de los correos de práctica y 
  pégalos en el prompt indicando "Aquí están los correos a analizar:"
- Nota: Esta alternativa limita la demostración de la integración M365, 
  pero permite completar el ejercicio de construcción de prompts
```

---

## Limpieza del Entorno

Una vez completado el laboratorio, realiza los siguientes pasos para limpiar el entorno de trabajo y evitar acumulación de datos de práctica en el tenant.

**Tiempo estimado:** 5 minutos

### Pasos de Limpieza

**1. Eliminar borradores de correo creados durante el laboratorio:**

```
1. Abre Microsoft Outlook
2. Ve a la carpeta "Borradores"
3. Selecciona todos los borradores creados durante el laboratorio 
   (identifícalos por la fecha/hora de creación de hoy)
4. Elimínalos con la tecla Delete o botón derecho > Eliminar
5. Vacía la carpeta "Elementos eliminados" para confirmar la limpieza
```

**2. Eliminar el plan de práctica en Microsoft Planner:**

```
1. Accede a Microsoft Planner: https://tasks.office.com
2. Localiza el plan creado durante el laboratorio (nombre del proyecto ficticio)
3. Haz clic en los tres puntos (...) junto al nombre del plan
4. Selecciona "Cerrar plan" o "Eliminar plan" según la opción disponible
5. Confirma la eliminación cuando se solicite
   NOTA: Esta acción es irreversible. Confirma que es el plan de práctica 
   y no un plan real de trabajo.
```

**3. Archivar (no eliminar) los archivos de OneDrive:**

```
1. Abre OneDrive: https://onedrive.live.com
2. Navega a la carpeta "Lab-Cowork-Practica"
3. NO elimines esta carpeta — contiene tu guía personal de delegación
4. Puedes eliminar los archivos de práctica proporcionados por el facilitador 
   si ya no los necesitas:
   - ventas_ficticias_Q3.xlsx
   - correos_practica_template.oft
   - descripcion_proyecto_ficticio.docx
5. CONSERVA: GuiaDelegacion_[TuNombre]_Lab01.docx
```

**4. Cerrar aplicaciones abiertas:**

```
- Cierra las pestañas adicionales del navegador abiertas durante el laboratorio
- Puedes mantener Teams, Outlook y Excel abiertos si los usas normalmente
- No es necesario cerrar sesión en las aplicaciones de Microsoft 365
```

---

## Resumen

### Lo que Aprendiste en este Laboratorio

En este taller de 70 minutos, exploraste de forma práctica y directa la distinción fundamental entre **Copilot Chat** (asistente de generación de contenido) y **Copilot Cowork** (agente de ejecución de trabajo autónomo). A través de tres casos de uso empresariales de alto impacto, experimentaste cómo Cowork puede absorber tareas operativas complejas que normalmente consumen horas de trabajo profesional.

Los conceptos clave que aplicaste:

| Concepto                         | Aplicación en el Laboratorio                                                                |
|----------------------------------|---------------------------------------------------------------------------------------------|
| **Agencia vs. Generación**       | Comparaste directamente ambas herramientas con la misma tarea y observaste la diferencia    |
| **Orquestación de agentes**      | Observaste los pasos intermedios de ejecución de Cowork en los tres casos de uso            |
| **Conectores de Microsoft Graph**| Cowork accedió a OneDrive, Outlook y Planner sin que copiaras datos manualmente             |
| **Prompts de delegación**        | Construiste instrucciones estructuradas con contexto, objetivo, pasos y formato de entrega  |
| **Perímetro de seguridad M365**  | Todas las acciones de Cowork ocurrieron dentro del tenant sin exponer datos externos        |

### Principios de Delegación Efectiva Consolidados

Basándote en la experiencia del taller, los prompts de delegación más efectivos para Copilot Cowork comparten estas características:

1. **Contexto claro:** Quién eres, cuál es tu rol y por qué necesitas la tarea.
2. **Objetivo específico:** Qué resultado final esperas, no solo qué acción realizar.
3. **Pasos estructurados:** Una lista numerada de acciones intermedias cuando la tarea es compleja.
4. **Formato de entregable:** Cómo debe presentarse el resultado (Word, tabla, borrador en Outlook, etc.).
5. **Restricciones explícitas:** Qué NO debe hacer Cowork (no enviar correos, no inventar datos, etc.).

### Próximos Pasos

- **Lección 1.2:** Profundiza en la distinción entre delegar trabajo y generar contenido con ejemplos avanzados de cada modelo.
- **Lección 1.3:** Explora los tipos de tareas que Copilot Cowork puede ejecutar y sus límites actuales.
- **Práctica autónoma:** Elige una tarea real de tu trabajo (con datos no sensibles) y aplica el modelo de delegación estructurada que practicaste hoy.

### Recursos Adicionales

| Recurso                                                                                                                                  | Descripción                                                    |
|------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| [Documentación oficial de Microsoft 365 Copilot](https://learn.microsoft.com/es-es/microsoft-365-copilot/microsoft-365-copilot-overview) | Introducción oficial a las capacidades de Copilot y Cowork     |
| [Microsoft Graph: Acceso a datos organizacionales](https://learn.microsoft.com/es-es/graph/overview)                                     | Cómo Cowork accede a los datos del tenant a través de Graph    |
| [Blog de Microsoft: Wave 2 de Copilot](https://www.microsoft.com/es-es/microsoft-365/blog/2024/09/16/introducing-microsoft-365-copilot-wave-2/) | Anuncio oficial de las capacidades de agente en M365 Copilot   |
| [Microsoft Copilot Studio — Orquestación de agentes](https://learn.microsoft.com/es-es/microsoft-copilot-studio/fundamentals-what-is-copilot-studio) | Arquitectura técnica de la orquestación de agentes en Copilot  |

---

*Laboratorio desarrollado para el Módulo 1.0 del curso de Microsoft 365 Copilot Cowork. Versión 1.0.*
