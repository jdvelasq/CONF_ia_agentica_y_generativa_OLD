# IA generativa y agéntica — Diapositivas

Cada sección `##` es una diapositiva lista para pegar en Claude o Codex para PowerPoint: se copia desde la línea "Crea una diapositiva" hasta el final de la sección. Las secciones están en el mismo orden que D01, D02… de `esquema.md`. El plan, los públicos y los pendientes están en `esquema.md`.

Al empezar una sesión en el complemento, pegar primero la sección **ESTILO**.

---

## ESTILO

Vamos a construir una presentación diapositiva por diapositiva. Aplica estas reglas a todas las diapositivas que te pida:

- Estilo de charla TEDx combinado con el formato académico afirmación–evidencia: el título es una afirmación completa de una o dos líneas, en letra grande (36 pt o más); el cuerpo es evidencia visual (imagen, diagrama o dato), no una lista de viñetas.
- Una sola idea por diapositiva. Mucho espacio vacío. Poco texto: solo los rótulos que te indique, con el texto exacto.
- Imagen dominante: ocupa la mayor parte de la diapositiva.
- Sin logotipos de empresas ni de productos; los nombres van solo como texto.
- Usa la plantilla abierta en el archivo. Si no hay plantilla, fondo blanco, texto gris oscuro y una tipografía sin serifas.
- Colores de acento por bloque: apertura y cierre, gris oscuro; línea de tiempo, azul; leer, decidir e instalar, turquesa; analítica y curso, verde; gestión académica, naranja; ventaja competitiva, morado; gobernanza, rojo. Usa el acento solo para resaltar lo que se está explicando.
- Cuando pida una "franja de línea de tiempo": una línea horizontal delgada en la parte superior con las marcas "Antes de 2017 · 2017 · 2020 · 2022 · 2023 · 2024 · 2025 · 2026", y resalta en el color de acento solo la marca indicada.
- Cuando pida un "recuadro de términos": un recuadro pequeño en una esquina inferior con cada término en negrita y su definición en una línea.
- Cuando pida un recuadro "Pruébelo": un recuadro con borde en el color de acento, en la parte inferior derecha, con la palabra "Pruébelo", el nombre de la herramienta en negrita y la instrucción entre comillas, en letra legible (16 pt o más). Es un ejemplo concreto que el público puede repetir.
- Cuando pida un "pie de fuente": texto de 10 pt en la parte inferior izquierda.
- Todo en español.

Confirma que entendiste y espera la primera diapositiva.

---

## Slide

Crea una diapositiva de portada.

Título: IA generativa y agéntica
Subtítulo: Un vocabulario y una gramática comunes para lo que viene
Autor: Juan David Velásquez-Henao
Institución: Facultad de Minas · Universidad Nacional de Colombia, Sede Medellín
Fecha: [fecha de la sesión]

Composición: título grande centrado a la izquierda; autor, institución y fecha abajo en letra pequeña.
Imagen: franja de línea de tiempo muy tenue en la parte superior, sin ninguna marca resaltada.
Color de acento: gris oscuro.

## Slide

Crea una diapositiva.

Título: Todos hemos visto la IA. Pocos sabemos qué estamos viendo.

Composición: collage a pantalla completa con el título superpuesto en una franja semitransparente.
Imagen: collage de seis publicaciones de redes sociales genéricas (sin marcas ni personas reales), cada una con una palabra resaltada: "ChatGPT", "MCP", "harness", "agentes", "skills", "tu propio Jarvis".
Rótulo inferior (texto exacto): Al final de esta sesión: un mismo vocabulario y una misma gramática para leer todo esto, decidir y actuar.
Color de acento: gris oscuro.

## Slide

Crea una diapositiva.

Título: La mayoría usa la IA para preguntar. La ventaja está en los peldaños de arriba.

Composición: diagrama de escalera ascendente de izquierda a derecha, ocupando dos tercios de la diapositiva.
Imagen: escalera de seis peldaños con estos rótulos (texto exacto), de abajo hacia arriba:
1. Preguntar
2. Redactar y resumir
3. Trabajar con documentos propios
4. Instrucciones reutilizables
5. Investigar con fuentes
6. Delegar flujos de trabajo
Marca una llave sobre los peldaños 1 y 2 con el rótulo "La mayoría está aquí" y otra sobre los peldaños 5 y 6 con el rótulo "Aquí está la ventaja" en el color de acento.
Color de acento: gris oscuro.

---

## Slide

Crea una diapositiva.

Título: Durante décadas, las máquinas contaron palabras. Contar no es entender.

Franja de línea de tiempo con "Antes de 2017" resaltado.
Composición: dos paneles lado a lado.
Panel izquierdo, rótulo "Minería de texto clásica": una nube de palabras hecha con comentarios de estudiantes sobre un curso (palabras como "clase", "profesor", "tareas", "mal", "bien", "difícil").
Panel derecho, rótulo "Un modelo de lenguaje": los mismos comentarios resumidos en tres temas, cada uno con una cita textual corta entre comillas.
Rótulo destacado bajo los paneles (texto exacto): "No estuvo nada mal la clase" → la minería clásica cuenta "mal" como negativo; un modelo de lenguaje entiende que es un elogio.
Rótulos pequeños bajo el panel izquierdo (texto exacto): Bolsa de palabras y TF-IDF · Sentimiento con diccionarios · Tópicos con LDA (2003) · Un modelo por tarea

Recuadro de términos:
- Bolsa de palabras: el texto como conteo de palabras, sin importar el orden.
- TF-IDF: peso alto para palabras frecuentes en un documento y raras en el resto.
- Análisis de sentimiento: clasificar un texto como positivo, negativo o neutro.
- Modelado de tópicos: descubrir temas por las palabras que aparecen juntas.

Pie de fuente: Salton (TF-IDF, años setenta); Blei, Ng y Jordan (LDA, 2003).
Recuadro Pruébelo: Gemini (cuenta institucional): "Te pego los comentarios abiertos de la evaluación docente de un curso. Agrúpalos en temas, indica el sentimiento de cada tema y cita dos comentarios textuales por tema."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Antes de ChatGPT ya existía casi todo. Faltaba que lo viéramos.

Franja de línea de tiempo con "2017" y "2020" resaltados.
Composición: imagen grande a la izquierda; a la derecha, cuatro rótulos alineados verticalmente sobre una línea de tiempo.
Imagen: el teclado de un celular sugiriendo la siguiente palabra, y la sugerencia que crece hasta convertirse en un párrafo completo.
Rótulos (texto exacto):
- 2017 · Transformer: la arquitectura de todos los modelos actuales
- 2018–2020 · BERT, GPT-3: más datos y más escala, mejores resultados
- 2020 · RAG: buscar en documentos antes de responder
- 2021 · Modelos fundacionales: un modelo base para muchas tareas

Recuadro de términos:
- LLM: modelo de lenguaje grande; genera texto prediciendo el siguiente fragmento.
- Token: fragmento de texto con el que el modelo lee, escribe y cobra.
- Embeddings: números que representan el significado de un texto.
- RAG: buscar en documentos propios y dárselos al modelo para responder.

Pie de fuente: Vaswani et al. (2017); Lewis et al. (2020); Bommasani et al., Stanford (2021).
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: El modelo ya existía. Lo nuevo fue poder conversar con él.

Franja de línea de tiempo con "2022" resaltado.
Composición: imagen dominante centrada; un rótulo grande con la fecha.
Imagen: interfaz de chat minimalista y genérica (sin marca) con una primera pregunta sencilla y el inicio de una respuesta.
Rótulos (texto exacto):
- 30 de noviembre de 2022
- Detrás: entrenamiento con retroalimentación humana para seguir instrucciones

Recuadro de términos:
- Prompt: la instrucción que se le da al modelo.
- RLHF: entrenamiento con retroalimentación humana para que siga instrucciones y converse.

Pie de fuente: OpenAI, InstructGPT (2022); lanzamiento de ChatGPT (30 nov. 2022).
Recuadro Pruébelo: ChatGPT: "Redacta un correo de bienvenida para la nueva cohorte de la Maestría en Analítica: tono cordial, máximo 150 palabras, con la fecha de inducción y el enlace al calendario."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Escribe con seguridad aunque no sepa.

Franja de línea de tiempo con "2023" resaltado.
Composición: imagen dominante; tres rótulos cortos debajo.
Imagen: una referencia bibliográfica en formato académico con un sello rojo que dice "No existe".
Rótulos (texto exacto):
- Inventa referencias
- No conoce lo reciente
- Olvida el comienzo de una conversación larga
Rótulo destacado (texto exacto): Junio de 2023: un tribunal de Nueva York sanciona a abogados que citaron casos inventados por ChatGPT en una demanda contra Avianca.

Recuadro de términos:
- Alucinación: respuesta plausible y bien redactada, pero falsa.
- Fecha de corte: hasta cuándo llegan los datos con que se entrenó.
- Ventana de contexto: cuánto texto puede tener en cuenta a la vez.

Pie de fuente: Mata v. Avianca, Tribunal del Distrito Sur de Nueva York (junio de 2023).
Recuadro Pruébelo: Cualquier chat sin búsqueda web: "Dame cinco artículos sobre deserción en posgrado en Colombia, con su DOI." Luego verifique cada DOI: algunos no existirán.
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Con búsqueda web, el modelo deja de recordar y empieza a consultar.

Franja de línea de tiempo con "2023" resaltado.
Composición: dos columnas lado a lado con la misma pregunta arriba, en letra grande y entre comillas.
Pregunta (texto exacto): "¿Qué es una tesis de maestría de profundización en la UNAL?"
Columna izquierda, encabezado "Sin búsqueda web": una respuesta segura y bien redactada que describe una "tesis de profundización", sin fuentes, con un sello rojo pequeño "Sin fuente".
Columna derecha, encabezado "Con búsqueda web", en el color de acento: una respuesta que dice que la Maestría de Profundización no tiene tesis sino trabajo final, de máximo el 20 % de los créditos, con el enlace al Acuerdo 033 de 2007 del CSU.
Rótulos bajo las columnas (texto exacto):
- Dic. 2022 – feb. 2023 · Perplexity y Bing Chat: respuestas con fuentes
- 2023–2025 · ChatGPT, Gemini y Claude agregan búsqueda web
- Resuelve "no sabe lo reciente"; no resuelve "hay que verificar"

Recuadro de términos:
- Búsqueda web (grounding): el modelo busca antes de responder y ancla la respuesta en fuentes con enlace.

Recuadro Pruébelo: En ChatGPT, Gemini o Claude, haga la pregunta "¿Qué es una tesis de maestría de profundización en la UNAL?" con la búsqueda web desactivada y luego activada. Compare: según el Acuerdo 033 de 2007, la Maestría de Profundización tiene trabajo final, no tesis.
Pie de fuente: Acuerdo 033 de 2007 del Consejo Superior Universitario, artículo 11.
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: No hay una IA: hay muchos modelos, y algunos se pueden descargar.

Franja de línea de tiempo con "2023" resaltado.
Composición: diagrama de dos lados separados por una línea vertical.
Lado izquierdo, rótulo "En la nube": una nube con los nombres GPT-4, Claude, Gemini.
Lado derecho, rótulo "En tu computador": un portátil con los nombres Llama, Mistral, Qwen, DeepSeek.
Rótulos bajo el diagrama (texto exacto):
- Mar. 2023 · GPT-4, Claude y Bard compiten en la nube
- Feb.–sep. 2023 · LLaMA, Llama 2 y Mistral: pesos abiertos
- Jul. 2023 · Ollama: un modelo en tu computador con un comando

Recuadro de términos:
- Pesos abiertos: el modelo se puede descargar y ejecutar en un equipo propio.
- Local vs. nube: dónde se ejecuta el modelo; en local, los datos no salen.
- Fine-tuning: ajustar un modelo existente con datos propios.

Recuadro Pruébelo: Ollama en el portátil: en la terminal, "ollama run gpt-oss:20b"; apague el wifi y pídale "resume esta acta en cinco puntos".
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Ya no solo lee: ve, escucha y habla.

Franja de línea de tiempo con "2023" y "2024" resaltados.
Composición: imagen dominante a la izquierda; tres rótulos a la derecha.
Imagen: un celular fotografiando un tablero con notas escritas a mano y, al lado, el resumen de esas notas en texto limpio.
Rótulos (texto exacto):
- Sep. 2022 · Whisper: transcribe voz, y se puede descargar
- Sep. 2023 · Entiende imágenes
- May. 2024 · Conversa por voz en tiempo real

Recuadro de términos:
- Multimodal: entiende o genera texto, imagen, audio y video.

Recuadro Pruébelo: Gemini en el celular: fotografíe el tablero al final de la clase y pida "convierte esto en apuntes ordenados, con los conceptos clave en negrita".
Color de acento: azul.

---

## Slide

Crea una diapositiva.

Título: El modelo no puede hacer nada… pero puede pedir que se haga.

Franja de línea de tiempo con "2023" resaltado.
Composición: diagrama horizontal de cuatro pasos, de izquierda a derecha, ocupando el centro.
Imagen: cuatro cajas conectadas por flechas:
1. "Pregunta: ¿cuántos créditos tiene una maestría?"
2. "El modelo pide: buscar_normativa('créditos maestría')"
3. "El sistema ejecuta y devuelve el resultado"
4. "El modelo responde con el dato"
Rótulos bajo el diagrama (texto exacto):
- Mar. 2023 · Plugins de ChatGPT y Auto-GPT
- Jun. 2023 · Function calling
- Ago. 2024 · Respuestas en formato fijo para programas

Recuadro de términos:
- Tools / function calling: el modelo pide ejecutar una función y recibe el resultado.
- Structured outputs: respuestas en un formato fijo que un programa puede leer.
- Gateway: intermediario para usar muchos modelos con una sola interfaz.

Recuadro Pruébelo: ChatGPT o Claude con búsqueda web: "¿Qué universidades colombianas ofrecen maestrías en analítica en modalidad híbrida? Tabla con universidad, modalidad y fuente de cada fila."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: La IA empieza a trabajar con lo tuyo.

Franja de línea de tiempo con "2023" y "2024" resaltados.
Composición: imagen dominante; tres rótulos debajo.
Imagen: una pila de documentos con etiquetas "Acuerdo", "Acta", "Programa" que alimenta una respuesta con notas al pie numeradas [1] [2] [3].
Rótulos (texto exacto):
- 2023 · NotebookLM, hoy Gemini Notebook: respuestas solo con tus fuentes, y con cita
- Nov. 2023 – ago. 2024 · GPTs, Proyectos de Claude, Gems: instrucciones guardadas para una tarea
- Feb. 2024 · Memoria entre conversaciones

Recuadro de términos:
- Asistente personalizado: instrucciones y archivos guardados para una tarea recurrente.
- Memoria: lo que el sistema recuerda de una conversación a otra.

Recuadro Pruébelo: Gemini Notebook: cargue el Acuerdo 033 de 2007 del CSU y pregunte "¿Qué porcentaje máximo de créditos puede tener el trabajo final de una Maestría de Profundización? Cita el artículo."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Pensar antes de responder también se puede entrenar.

Franja de línea de tiempo con "2024" resaltado.
Composición: imagen dominante centrada; dos rótulos debajo.
Imagen: interfaz de chat genérica con un bloque desplegado que dice "Pensando…" y muestra tres pasos de razonamiento antes de la respuesta.
Rótulos (texto exacto):
- Sep. 2024 · Primer modelo presentado como "de razonamiento"
- Ene. 2025 · DeepSeek-R1: razonamiento con pesos abiertos
Rótulo pequeño (texto exacto): Mejor en problemas difíciles · más lento · más costoso

Recuadro de términos:
- Modelo de razonamiento: dedica tiempo a "pensar" antes de responder.
- Chain-of-thought: razonar paso a paso antes de dar la respuesta.

Recuadro Pruébelo: Claude o ChatGPT con razonamiento: "Con estas inscripciones previstas por electiva, ¿qué combinación de cinco electivas evita grupos de menos de diez estudiantes? Muestra el razonamiento."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Si una persona lo hace con mouse y teclado, un agente puede intentarlo.

Franja de línea de tiempo con "2024" resaltado.
Composición: captura grande de un navegador; un rótulo de advertencia abajo.
Imagen: ventana de navegador con un formulario web, un cursor y los pasos 1, 2, 3 numerados sobre los campos que va llenando.
Rótulos (texto exacto):
- Oct. 2024 · Computer use
- 2025 · Agentes que navegan sitios web y completan tareas
Rótulo de advertencia en el color de acento (texto exacto): El agente actúa con tus permisos.

Recuadro de términos:
- Computer use / browser use: el agente opera la pantalla o el navegador como una persona.

Recuadro Pruébelo: ChatGPT Agent o Claude en Chrome: "Entra al sitio público del SNIES y lista los programas de maestría en analítica activos en Antioquia, con su código."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Un enchufe estándar para conectar cualquier agente con cualquier sistema.

Franja de línea de tiempo con "2024" resaltado.
Composición: diagrama de dos paneles, "Antes" y "Después".
Panel "Antes": cuatro agentes a la izquierda y cuatro sistemas a la derecha (correo, documentos, base de datos, calendario), con líneas cruzadas entre todos.
Panel "Después": los mismos agentes y sistemas, todos conectados a un punto central rotulado "MCP".
Rótulos (texto exacto):
- 25 nov. 2024 · Estándar abierto
- Dic. 2025 · Pasa a una fundación neutral

Recuadro de términos:
- MCP: estándar abierto para conectar agentes con herramientas y datos.
- Conector: integración lista para un servicio concreto.

Pie de fuente: Anthropic, Model Context Protocol (2024); Linux Foundation (2025).
Recuadro Pruébelo: Claude con el conector de draw.io: "Dibuja el flujo de aprobación de una nueva asignatura, desde la propuesta del profesor hasta el consejo de facultad."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: La IA generativa responde. La IA agéntica actúa.

Composición: diagrama de dos columnas que ocupa toda la diapositiva.
Columna izquierda, rótulo "Generativa": una flecha recta de "Pregunta" a "Respuesta".
Columna derecha, rótulo "Agéntica": de "Objetivo" sale un ciclo de cuatro pasos alrededor de un círculo central "Modelo": "Decidir" → "Usar herramienta" → "Observar" → "Verificar", y del ciclo sale una flecha a "Resultado".
Resalta la columna derecha en el color de acento.

Recuadro de términos:
- Agente: un modelo que decide, usa herramientas y observa en ciclo hasta cumplir un objetivo.

Recuadro Pruébelo: Compare. Generativa: "Redacta un acta a partir de estas notas." Agéntica: "Revisa la carpeta de grabaciones de esta semana, transcribe cada comité y deja un acta por reunión en la carpeta Actas."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: No todo necesita un agente: empezar por lo más simple que funcione.

Franja de línea de tiempo con "2024" resaltado.
Composición: un control deslizante horizontal grande en el centro.
Imagen: control deslizante con cuatro posiciones rotuladas (texto exacto): "Asistente", "Flujo de trabajo", "Agente", "Agente persistente". Sobre el extremo izquierdo, "Más control"; sobre el derecho, "Más autonomía y más riesgo".
Rótulo bajo el control (texto exacto): Patrones: encadenar · enrutar · paralelizar · orquestar · evaluar y corregir

Recuadro de términos:
- Flujo de trabajo: una persona define los pasos; el modelo ejecuta cada uno.
- Niveles de autonomía: cuánto decide el sistema sin una persona.
- Patrones agénticos: formas recurrentes de organizar modelos y herramientas.

Pie de fuente: Anthropic, "Building effective agents" (dic. 2024).
Color de acento: azul.

---

## Slide

Crea una diapositiva.

Título: Una tarde de búsqueda, en minutos. Las fuentes, igual hay que revisarlas.

Franja de línea de tiempo con "2024" y "2025" resaltados.
Composición: imagen dominante; dos rótulos debajo.
Imagen: un informe de varias páginas con fuentes numeradas al margen; varias marcadas con un visto verde "verificada" y una con un signo de alerta "revisar".
Rótulos (texto exacto):
- Varias rondas de búsqueda, lectura y síntesis
- Uso académico: programas similares, tendencias, normativa

Recuadro de términos:
- Deep research: agente que investiga en varias rondas y entrega un informe con fuentes.

Recuadro Pruébelo: Gemini Deep Research (cuenta institucional): "Panorama de maestrías en analítica de negocios en América Latina que incluyan IA agéntica en su plan de estudios: universidad, modalidad, créditos y fuente."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: La misma pregunta en Gemini: una respuesta en segundos o un informe en minutos.

Composición: dos columnas lado a lado con la misma pregunta escrita arriba de ambas, en letra grande y entre comillas.
Pregunta (texto exacto): "¿Qué maestrías en analítica en Colombia se ofrecen en modalidad híbrida y cómo se comparan en créditos?"
Columna izquierda, encabezado "Búsqueda normal" (texto exacto):
- Segundos
- Pocas fuentes
- Una respuesta de un párrafo o una lista
- Sirve para un dato puntual
Columna derecha, encabezado "Deep Research", en el color de acento (texto exacto):
- Primero muestra un plan de investigación que se puede editar
- Varios minutos
- Decenas de fuentes leídas
- Un informe de varias páginas con tabla y referencias
- Sirve para un panorama que alimenta una decisión
Imagen: bajo cada columna, una miniatura de la salida correspondiente: un párrafo corto a la izquierda; un informe de varias páginas a la derecha.
Rótulo inferior (texto exacto): En ambos casos, las fuentes se revisan antes de usarlas.

Recuadro Pruébelo: Gemini (cuenta institucional): escriba la pregunta una vez como chat normal y otra vez activando Deep Research. Compare cuántas fuentes usó cada uno y qué programas encontró que el otro no.
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: "Hice una app sin saber programar": qué hay de cierto.

Franja de línea de tiempo con "2025" resaltado.
Composición: captura grande de una terminal; rótulos a la derecha.
Imagen: ventana de terminal con una conversación con un agente que crea y modifica archivos, mostrando mensajes como "Creé informe.md" y "Ejecuté las pruebas".
Rótulos (texto exacto):
- Feb. 2025 · Claude Code y el término "vibe coding"
- Abr.–jun. 2025 · Codex, Copilot en modo agente, Gemini CLI
- Lee, escribe y ejecuta en un proyecto real. También sirve para documentos.

Recuadro de términos:
- Harness: el programa que pone a trabajar al modelo con contexto, herramientas y permisos.
- Coding agent: agente que trabaja sobre los archivos de un proyecto.
- Vibe coding: construir describiendo lo que se quiere, sin revisar el código.
- Hosted agent: agente que corre en los servidores del proveedor.

Recuadro Pruébelo: Claude Code o Codex, en una carpeta con un documento por secciones: "Lee todos los archivos y lista cada cifra que no tenga fuente y año, con el archivo y la línea."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Claude Code no es un modelo: es un harness que usa un modelo.

Composición: diagrama de cuatro capas horizontales apiladas que ocupa toda la diapositiva.
Capas, de arriba hacia abajo (texto exacto):
- Superficie: por dónde se opera (chat, terminal, Office)
- Harness: lo pone a trabajar en un ciclo (Claude Code, Codex, opencode, Cowork)
- Modelo: predice y genera (Claude, GPT, Gemini, Qwen)
- Runtime: dónde corre (nube, tu computador)
Dos líneas verticales atraviesan las capas:
- Línea 1, rótulo "Claude Code": terminal → Claude Code → Claude → nube
- Línea 2, rótulo "opencode local", en el color de acento: terminal → opencode → Qwen → tu computador

Recuadro de términos:
- Modelo · Harness · Superficie · Runtime: las cuatro capas de cualquier producto de IA.

Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Un agente puede repartir el trabajo entre otros agentes.

Franja de línea de tiempo con "2025" resaltado.
Composición: diagrama tipo organigrama centrado.
Imagen: un agente coordinador arriba y tres agentes abajo con los rótulos "Investigar", "Redactar", "Revisar".
Rótulos (texto exacto):
- Subagentes: cada uno con su propio contexto
- Abr. 2025 · A2A: agentes de distintos proveedores colaborando

Recuadro de términos:
- Subagentes / multiagente: un agente reparte la tarea entre otros.
- A2A: protocolo para que agentes de distintos proveedores se comuniquen.

Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Lo que importa no es la pregunta, sino todo lo que el modelo tiene a la vista.

Franja de línea de tiempo con "2025" resaltado.
Composición: diagrama de embudo centrado.
Imagen: embudo al que entran cinco flujos rotulados "Instrucciones", "Documentos", "Herramientas", "Historial", "Decisiones ya tomadas", y del que sale una flecha hacia "Modelo".
Rótulo bajo el diagrama (texto exacto): Ejemplo real: un archivo de instrucciones guió la actualización curricular de la Maestría en Analítica.

Recuadro de términos:
- Ingeniería de contexto: diseñar toda la información que recibe el modelo, no solo la pregunta.

Pie de fuente: Anthropic, "Effective context engineering for AI agents" (sep. 2025).
Recuadro Pruébelo: Antes de pedir nada, escriba un archivo de instrucciones: "Este documento lo leen pares académicos. Usa la terminología del Acuerdo 033 de 2007. Nunca inventes cifras: cada cifra va con fuente y año."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Una skill empaqueta "cómo hacemos esto aquí" para que el agente lo reutilice.

Franja de línea de tiempo con "2025" resaltado.
Composición: imagen dominante a la izquierda; rótulos a la derecha.
Imagen: una carpeta abierta que contiene tres archivos: "SKILL.md", "plantilla.docx", "verificar.py".
Rótulos (texto exacto):
- Oct. 2025 · Agent Skills: el agente las carga solo cuando las necesita
- Dic. 2025 · Estándar abierto entre agentes
- Para la facultad: una skill por tipo de documento institucional

Recuadro de términos:
- Skill: carpeta con instrucciones, plantillas y scripts que el agente usa bajo demanda.
- Plugin: paquete que agrega skills, comandos o conectores a un agente.

Recuadro Pruébelo: Claude: cree una skill "acta-de-comite" con la plantilla de actas de la facultad. Después: "Haz el acta de esta transcripción usando la skill acta-de-comite."
Color de acento: azul.

---

## Slide

Crea una diapositiva.

Título: Lo que los agentes hicieron con el código en 2025, lo hacen con el trabajo de oficina en 2026.

Franja de línea de tiempo con "2026" resaltado.
Composición: imagen dominante a pantalla completa; rótulos en una franja inferior.
Imagen: un escritorio de computador donde un agente trabaja al mismo tiempo en un correo, una hoja de cálculo y un documento, con indicadores de progreso en cada ventana.
Rótulos (texto exacto):
- Ene.–mar. 2026 · Claude Cowork y Dispatch: delegar desde el escritorio o el celular
- Ene. 2026 · Gemini en Chrome
- Abr.–jul. 2026 · Workspace Agents y ChatGPT Work

Recuadro Pruébelo: Claude Cowork: "Organiza la carpeta Material del curso por semanas, renombra los archivos con un formato común y crea un índice en Word."
Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Agentes que nunca se apagan. ¿Cuánto acceso les daríamos?

Franja de línea de tiempo con "2026" resaltado.
Composición: imagen dominante a la izquierda; rótulos y tres preguntas a la derecha.
Imagen: un celular de noche con notificaciones de un agente: "Respondí 4 correos", "Agendé una reunión", "Pagué una factura".
Rótulos (texto exacto):
- Abiertos: OpenClaw, Hermes Agent, OpenJarvis
- De proveedores: Gemini Spark, Microsoft Autopilot, OpenAI dots, Meta Muse
Preguntas destacadas en el color de acento (texto exacto):
- ¿Qué permisos tiene?
- ¿Dónde guarda la memoria?
- ¿Quién responde por lo que hace?

Recuadro de términos:
- Agente personal persistente: corre siempre, recuerda, accede a tus cuentas y actúa por iniciativa propia.

Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Los proveedores ya diseñan productos para universidades y docentes.

Franja de línea de tiempo con "2025" y "2026" resaltados.
Composición: línea de tiempo horizontal grande en el centro con cinco hitos.
Hitos (texto exacto):
- Abr. 2025 · Claude for Education
- Ene. 2026 · Prism: escritura científica en LaTeX
- Jun. 2026 · Claude Science
- Jul. 2026 · Claude for Teachers
- Hoy · Gemini para Educación, la licencia que ya tenemos (resáltalo en el color de acento)

Color de acento: azul.

## Slide

Crea una diapositiva.

Título: Seis preguntas antes de creerle a un anuncio.

Composición: imagen de un anuncio en el centro, con seis preguntas numeradas alrededor conectadas por líneas finas.
Imagen: anuncio genérico de redes sociales que dice "¡Tu agente con MCP que lo hace todo!".
Preguntas (texto exacto):
1. ¿Qué capa es?
2. ¿Qué modelo usa por debajo?
3. ¿Dónde quedan los datos?
4. ¿Qué permisos pide?
5. ¿Es producto, vista previa o demo?
6. ¿Qué problema mío resuelve?

Color de acento: azul.

---

## Slide

Crea una diapositiva.

Título: Con cinco estructuras se puede leer cualquier herramienta, anuncio o caso.

Composición: cinco columnas iguales que ocupan toda la diapositiva; una línea horizontal en el color de acento atraviesa las cinco columnas a media altura.
Columnas (encabezado y pregunta, texto exacto):
1. Las cuatro capas · ¿Qué es?
2. El ciclo del agente · ¿Cómo funciona?
3. Niveles de autonomía · ¿Cuánto decide solo?
4. Escalera de uso · ¿Para qué lo uso?
5. Clasificación de datos · ¿Dónde pongo esta información?
Sobre la línea, en cada columna, el ejemplo "Claude Cowork" (texto exacto):
1. Escritorio + Cowork + Claude + nube
2. Decide, usa herramientas, verifica
3. Agente
4. Peldaño 6
5. Información pública o interna con acuerdo institucional
Rótulo inferior (texto exacto): Vocabulario = las palabras. Gramática = cómo se combinan.

Color de acento: turquesa.

## Slide

Crea una diapositiva.

Título: "Una skill para que Claude use Perplexity": en dos minutos se sabe si sirve.

Composición: a la izquierda (40 %), un anuncio genérico de redes sociales; a la derecha (60 %), una ficha de seis filas con pregunta y respuesta.
Imagen del anuncio: publicación genérica que dice "Claude + Perplexity: búsqueda web superpoderosa con una skill".
Ficha (texto exacto, pregunta en negrita y respuesta al lado):
1. ¿Qué capa es? Una integración. No es un modelo nuevo.
2. ¿Qué modelo hay detrás? Dos: Claude decide qué buscar; Perplexity busca y cita.
3. ¿Dónde quedan los datos? Las consultas salen a Perplexity: solo información pública.
4. ¿Qué permisos pide? Internet con una clave de API; si trae scripts, ejecuta código.
5. ¿Producto o demo? Existe un conector oficial de Perplexity; preferirlo a copias.
6. ¿Me sirve? Sí, si vigilo programas o normativa desde Claude. No, si basta Perplexity gratis.
Rótulo inferior en el color de acento (texto exacto): Decisión: conector oficial, solo información pública, y la clave de API se paga aparte de la suscripción.

Pie de fuente: Perplexity, documentación del servidor MCP oficial.
Color de acento: turquesa.

## Slide

Crea una diapositiva.

Título: Instalar una skill o un conector toma minutos. Revisarlo antes, también.

Composición: arriba, tres columnas con la ruta de instalación; abajo, una lista de verificación horizontal con cinco casillas.
Columnas (encabezado y texto exacto):
- App de Claude: subir la skill como ZIP en la sección de skills y activarla
- Claude Code: carpeta ~/.claude/skills/, comando /plugin, o claude mcp add para un conector
- Codex, Gemini CLI y otros: su propia carpeta de skills; mismo formato SKILL.md
Lista de verificación (texto exacto):
☐ ¿Quién la publica?
☐ Leí el SKILL.md y los scripts
☐ ¿Qué permisos y claves pide? ¿Cuánto cuesta?
☐ La probé con información pública
☐ Sé cómo desinstalarla

Recuadro de términos:
- Clave de API: credencial con la que un programa usa un servicio y se cobra el consumo; no es la suscripción.

Pie de fuente: Anthropic, centro de ayuda "Use skills in Claude"; Perplexity, documentación MCP.
Color de acento: turquesa.

## Slide

Crea una diapositiva.

Título: El mismo método sirve para lo que un profesor hace cada semana.

Composición: cinco tarjetas tipo anuncio en una cuadrícula; cada tarjeta tiene abajo tres sellos pequeños: la capa, un punto de color (verde = público, amarillo = interno, rojo = sensible) y "Me sirve para…".
Tarjetas (texto exacto: anuncio · capa · color · me sirve para):
1. "Claude ahora hace diagramas en draw.io" · Conector MCP · verde · diagramas de procesos y flujos para clase
2. "Presentaciones de clase en minutos" · Complemento de Office o skill · verde · preparar y actualizar diapositivas
3. "Tu curso convertido en guía de estudio y podcast" · Gemini Notebook · amarillo · guías, audios y cuestionarios
4. "Retroalimentación de trabajos con IA" · Gem o skill con rúbrica · rojo · borradores de comentarios; la nota la pone el profesor
5. "Transcribe tus clases" · Whisper en tu equipo · rojo · apuntes y subtítulos sin que la grabación salga
Rótulo inferior (texto exacto): ¿Cuál clasificaría usted primero?

Pie de fuente: draw.io, "draw.io MCP server and plugins for AI assistants".
Color de acento: turquesa.

---

## Slide

Crea una diapositiva.

Título: La IA agéntica toca cada fase del trabajo analítico, no solo el modelado.

Composición: diagrama circular grande con siete segmentos; debajo, tres franjas horizontales.
Segmentos del círculo (texto exacto, en orden): Problema de negocio · Problema analítico · Datos · Metodología · Modelado · Despliegue · Ciclo de vida
Franjas bajo el círculo (texto exacto): DataOps · MLOps · Código limpio

Pie de fuente: INFORMS, dominios de la certificación Certified Analytics Professional.
Color de acento: verde.

## Slide

Crea una diapositiva.

Título: El problema llega desordenado. La IA ayuda a ordenarlo, no a decidirlo.

Composición: diagrama de izquierda a derecha.
Izquierda: notas sueltas, correos y la transcripción de una reunión, desordenados.
Derecha: una tabla limpia con cuatro columnas rotuladas "Problema central", "Síntomas", "Causas posibles", "Supuestos".
Flecha entre ambos con el rótulo "Modelo local con tus documentos".
Rótulos bajo el diagrama (texto exacto):
- Preguntarle a las actas y reportes previos, con cita a la fuente
- Traducir la meta de negocio en una tarea analítica con entradas, salidas y métrica

Recuadro Pruébelo: Open WebUI con un modelo local: pegue transcripciones y correos y pida "extrae el problema central, los síntomas, las posibles causas y los supuestos de cada persona, en una tabla".
Color de acento: verde.

## Slide

Crea una diapositiva.

Título: Un análisis exploratorio en minutos, con el código para repetirlo.

Composición: captura grande a la izquierda; rótulos a la derecha.
Imagen: terminal de un agente junto a tres gráficos generados (un histograma, una matriz de correlación y un diagrama de cajas) y un resumen de cinco hallazgos numerados.
Rótulos (texto exacto):
- El agente escribe, ejecuta y resume el análisis
- Perfila calidad, faltantes, duplicados y sesgos
- Documenta la preparación mientras la hace

Recuadro Pruébelo: opencode o Claude Code: "Genera un análisis exploratorio de datos.csv: distribuciones, correlaciones y valores atípicos; guarda los gráficos y resume los cinco hallazgos más relevantes."
Color de acento: verde.

## Slide

Crea una diapositiva.

Título: El agente propone y ejecuta. El analista juzga.

Composición: tabla de comparación grande en el centro.
Tabla: filas "Línea base", "Modelo A", "Modelo B"; columnas "Desempeño", "Interpretabilidad", "Costo", "Datos requeridos", con íconos de nivel (alto, medio, bajo). La columna de decisión final se titula "Decide el analista" en el color de acento.
Rótulos bajo la tabla (texto exacto):
- Primero una línea base simple
- Detectar fuga de información
- Analizar errores por segmentos

Color de acento: verde.

## Slide

Crea una diapositiva.

Título: Del notebook que funciona a la solución que sigue funcionando.

Composición: línea de tiempo horizontal con cuatro etapas.
Etapas (texto exacto): Despliegue → Monitoreo → Alerta de degradación → Recalibración
Rótulos bajo la línea (texto exacto):
- Explicar resultados a quienes deciden
- Guías de uso y procedimientos de operación
- Documentación siempre al día

Color de acento: verde.

## Slide

Crea una diapositiva.

Título: El agente convierte el notebook improvisado en un pipeline mantenible.

Composición: antes y después, lado a lado.
Antes: un notebook largo con muchas celdas desordenadas y nombres como "df2", "temp", "final_v3".
Después: una estructura de carpetas limpia: "datos/", "src/", "pruebas/", "pipeline.yml".
Rótulos (texto exacto):
- Refactorizar en módulos con pruebas
- Versionar datos, modelos y pipelines
- Revisar el código antes de integrar cambios

Color de acento: verde.

---

## Slide

Crea una diapositiva.

Título: Las mejores universidades ya enseñan a construir agentes. La Facultad de Minas también.

Franja de línea de tiempo con "2024", "2025" y "2026" resaltados.
Composición: línea de tiempo horizontal con los cursos; el último hito destacado.
Hitos (texto exacto):
- 2024 · Berkeley: Large Language Model Agents
- 2025 · Berkeley: Advanced LLM Agents · Stanford: Self-Improving AI Agents
- 2026 · Stanford: Agentic AI, Engineering AI Agents · Carnegie Mellon: Agentic Technology
- Facultad de Minas: IA generativa y agéntica para analítica (propuesta), en el color de acento

Recuadro de términos:
- Ingeniería de sistemas agénticos: diseñar, construir, evaluar y operar sistemas de agentes con rigor de ingeniería.

Color de acento: verde.

## Slide

Crea una diapositiva.

Título: Este vocabulario común es el punto de partida. El curso llega hasta la ingeniería de sistemas agénticos.

Composición: un camino horizontal con solo dos puntos marcados y el tramo intermedio punteado.
Punto de inicio (texto exacto): Vocabulario y gramática comunes
Punto de llegada, en el color de acento (texto exacto): Diseñar, construir, evaluar y operar sistemas agénticos para la analítica
Tramo intermedio (texto exacto): Lo construimos juntos

Color de acento: verde.

---

## Slide

Crea una diapositiva.

Título: La universidad ya tiene la puerta de entrada. Falta usarla a fondo.

Composición: tabla de cuatro filas y tres columnas que ocupa el centro.
Encabezados de columna (texto exacto): Sin costo (Fundamentals) · Education Plus · Complemento AI Pro
Filas (texto exacto, con ✓ o — en cada celda):
- App Gemini: chat, Gems, Deep Research · ✓ con límites · ✓ con límites · ✓ más uso
- Gemini Notebook: respuestas solo con tus fuentes · ✓ con topes diarios · ✓ topes más altos · ✓ topes más altos
- Gemini en Docs, Sheets, Slides y Forms · — · ✓ · ✓
- Gemini en Gmail, Meet, Drive y Chat · — · — · ✓
Rótulo destacado en el color de acento (texto exacto): Con la cuenta institucional, los datos no se usan para entrenar modelos ni los revisan personas.

Pie de fuente: Google Workspace, "Quickstart Guide to Gemini and Gemini Notebook for Education"; Google for Education, "Compare Editions" (oct. 2026).
Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: Gemini es la base. Cada herramienta tiene su fuerte.

Composición: tabla de cinco filas y tres columnas.
Encabezados (texto exacto): Herramienta · Su fuerte · Gratis
Filas (texto exacto):
- Perplexity · Buscar con fuentes citadas · Búsquedas básicas ilimitadas
- Claude · Documentos largos, Office y agentes de escritorio · Chat y hasta 5 proyectos
- ChatGPT / Codex · La más conocida; agentes de código y documentos · Chat diario; Codex limitado
- DeepSeek y modelos abiertos · Bajo costo; se ejecutan en tu equipo · Chat web y modelos descargables
- Gemini (cuenta personal) · Integración con Google; Gemini CLI · Chat, Notebook y Gemini CLI
Rótulo inferior en el color de acento (texto exacto): Las versiones gratuitas sirven para información pública. Nunca para datos institucionales.

Pie de fuente: páginas de cada proveedor y guías de terceros (oct. 2026); límites aproximados.
Recuadro Pruébelo: Perplexity: "¿Qué cambió en la normativa de registro calificado en Colombia entre 2025 y 2026? Con fuentes oficiales." Y luego, Claude: "Con estas fuentes, redacta una nota de dos párrafos para el comité."
Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: Hay datos que no deben salir de la facultad, y no tienen por qué hacerlo.

Composición: imagen dominante a la izquierda; rótulos a la derecha.
Imagen: un portátil con el ícono de wifi apagado; dentro de la pantalla, documentos rotulados "Notas", "Actas", "Solicitudes"; afuera, una nube tachada.
Rótulos (texto exacto):
- Datos de estudiantes (Ley 1581 de 2012), actas, evaluaciones, propuestas no aprobadas
- Un portátil con 36 GB de memoria ejecuta modelos de unos 30 mil millones de parámetros
- Chatear, preguntar a documentos, transcribir y usar agentes, sin internet
Rótulo inferior en el color de acento (texto exacto): Lo sensible en local. Lo público en la nube.

Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: Tareas de cada semana que ya se pueden delegar en parte.

Composición: cuatro tarjetas en cuadrícula de dos por dos; cada tarjeta con un ícono, el caso y, abajo, la herramienta.
Tarjetas (texto exacto: caso · herramienta):
1. Responder solicitudes estudiantiles con la normativa citada · Gemini Notebook
2. Actas a partir de grabaciones de comités · Whisper en el equipo
3. Informes de gestión desde hojas de cálculo y documentos · Gemini en Sheets y Docs
4. Respuestas a preguntas frecuentes sobre normativa · Gem

Recuadro Pruébelo: Gemini Notebook con la normativa estudiantil cargada: "Un estudiante pide cancelar una asignatura fuera de fechas. ¿Qué dice la norma? Redacta una respuesta citando el artículo."
Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: Del microcurrículo al comité curricular, con evidencia a la mano.

Composición: cuatro tarjetas en cuadrícula de dos por dos, igual que la diapositiva anterior.
Tarjetas (texto exacto: caso · herramienta):
1. Revisar la alineación entre resultados de aprendizaje del programa y de las asignaturas · Gemini Notebook
2. Comparar el programa con programas similares del país y del mundo · Perplexity o Deep Research
3. Analizar matrícula, deserción y graduación · Gemini en Sheets
4. Preparar el material del comité curricular · Gemini en Docs y Slides

Recuadro Pruébelo: Gemini Notebook con el proyecto educativo del programa y los microcurrículos: "¿Qué resultados de aprendizaje del programa no se desarrollan en ninguna asignatura? Tabla con resultado y evidencia."
Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: Un documento institucional de 25 secciones, construido con un agente.

Composición: imagen dominante con una lista de 25 archivos numerados; rótulos a la derecha.
Imagen: listado de archivos con nombres como "01-justificacion-de-la-propuesta.md", "02-prospectiva-y-pertinencia-del-programa.md", "14-resultados-de-aprendizaje-del-programa.md", "25-plan-de-transicion.md".
Rótulos (texto exacto):
- Las 25 secciones que exige la Vicerrectoría Académica
- De un borrador a un documento consolidado en una jornada
- Normativa, evidencia de mercado y decisiones, todas trazables

Pie de fuente: Actualización curricular de la Maestría en Ingeniería – Analítica, Facultad de Minas (oct. 2026).
Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: Cada concepto de la línea de tiempo, en acción.

Composición: diagrama de dos columnas unidas por flechas; la columna derecha en el color de acento.
Pares (texto exacto: práctica → concepto):
- Un archivo de instrucciones con objetivo, fuentes y reglas → Ingeniería de contexto
- La normativa como fuente → Trabajar con documentos propios
- Búsqueda de programas competidores → Deep research
- Cada cifra con fuente y año → Control de alucinaciones
- Cada cambio versionado → Observabilidad
- Reglas de redacción y terminología → Skill

Recuadro de términos:
- Observabilidad: dejar registro para reconstruir qué hizo el agente y por qué.

Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: El agente propone y avisa. La persona decide.

Composición: diagrama de dos carriles horizontales: arriba "Agente", abajo "Persona"; flechas entre carriles en los momentos de decisión.
Momentos (texto exacto):
1. Agente: "El trabajo final queda en 22,7 %; el máximo del Acuerdo 033 de 2007 es 20 %." → Persona: decide cómo ajustar los créditos
2. Persona: fija 40 créditos por plan → Agente: lo propaga a todas las secciones
3. Agente: "Elegir las asignaturas del plan de investigación no me corresponde." → Persona: lo lleva al comité asesor

Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: Si sirve para una actualización curricular, sirve para una autoevaluación.

Composición: a la izquierda, una plantilla de cinco piezas apiladas; a la derecha, tres documentos que salen de ella.
Piezas (texto exacto): Fuentes normativas · Evidencia · Reglas de redacción · Secciones fijas · Revisión humana
Documentos (texto exacto):
- Autoevaluación con fines de acreditación
- Renovación de registro calificado
- Informes de gestión y planes de mejoramiento

Pie de fuente: Acuerdo 02 de 2020 del CESU (factores de evaluación).
Color de acento: naranja.

## Slide

Crea una diapositiva.

Título: El mismo agente, al revés: revisar en vez de redactar.

Composición: a la izquierda, una propuesta; a la derecha, una rúbrica con cinco criterios y anotaciones por criterio; abajo, una flecha hacia "Comité o consejo decide".
Tipos de propuesta (texto exacto, como etiquetas sobre la propuesta): Nuevo programa · Asignatura · Diplomado · Curso de extensión
Criterios de la rúbrica (texto exacto): Normativa · Pertinencia · Coherencia con resultados de aprendizaje · Duplicidad con la oferta actual · Viabilidad

Recuadro de términos:
- Evals: casos de prueba para medir si un sistema de IA funciona.
- LLM como juez: un modelo que evalúa según criterios definidos.

Recuadro Pruébelo: Claude: "Evalúa esta propuesta de diplomado con la rúbrica adjunta. Para cada criterio: puntaje, evidencia citada del documento y qué le falta. No des una recomendación final."
Color de acento: naranja.

## Slide

Crea una diapositiva de transición.

Título: Veámoslo funcionar.

Composición: título muy grande centrado; debajo, cuatro palabras pequeñas separadas por puntos.
Texto pequeño (texto exacto): Contexto · Fuentes · Verificación · Decisión humana
Sin imagen.
Color de acento: naranja.

---

## Slide

Crea una diapositiva.

Título: La herramienta está al alcance de todos. La ventaja es de quien aprende a usarla primero.

Composición: curva de adopción en forma de S que ocupa la diapositiva.
Imagen: curva con tres tramos rotulados "Pioneros", "Mayoría", "Rezagados"; un punto en el color de acento en el tramo de pioneros con el rótulo "Facultad de Minas, hoy".
Rótulos (texto exacto):
- 2025–2026: los agentes llegan a la oficina y a la academia
- Las universidades de referencia ya forman en esto
- La diferencia ya no es el acceso, es la capacidad instalada

Color de acento: morado.

## Slide

Crea una diapositiva.

Título: La ventaja se construye en la oferta, en la operación y en la proyección.

Composición: tres columnas iguales, cada una con un ícono grande arriba.
Columnas (encabezado y texto exacto):
- Oferta académica: programas con IA agéntica en el núcleo
- Operación académica: documentos, evaluaciones y acreditación con agentes
- Proyección externa: diplomados y cursos de extensión para otras facultades, empresas y el sector público

Color de acento: morado.

## Slide

Crea una diapositiva.

Título: No partimos de cero.

Composición: línea de tiempo corta arriba; cuatro tarjetas abajo.
Línea de tiempo (texto exacto): 2014 · Especialización en Analítica → 2018 · Maestría en Ingeniería – Analítica → 2026 · Actualización con IA agéntica
Tarjetas (texto exacto):
- Pioneros en analítica de posgrado en el país
- Propuestas con IA agéntica en el núcleo: Maestría en Analítica y Especialización en Ingeniería de Software Agéntica
- Docencia propia en IA generativa y agéntica
- Licencia institucional de Gemini y un caso real construido con agentes

Pie de fuente: Facultad de Minas, documento de actualización de la Maestría en Ingeniería – Analítica (2026).
Color de acento: morado.

## Slide

Crea una diapositiva.

Título: De pilotos a capacidad institucional.

Composición: camino horizontal con cinco hitos, de izquierda a derecha.
Hitos (texto exacto):
1. Pilotar: dos o tres casos de la Vicedecanatura con Gemini institucional
2. Empaquetar: una skill por tipo de documento
3. Equipar: portátiles con IA local en las dependencias
4. Formar: subir a las personas en la escalera de uso
5. Gobernar: lineamientos de uso y clasificación de datos

Color de acento: morado.

## Slide

Crea una diapositiva.

Título: Lo que no se mide, no se sostiene.

Composición: tablero de cuatro indicadores en cuadrícula de dos por dos, cada uno con un ícono y un espacio para la cifra.
Indicadores (texto exacto):
- Tiempo de elaboración por tipo de documento
- Documentos y propuestas procesados con el patrón
- Personas en cada peldaño de la escalera
- Errores detectados en la revisión humana

Color de acento: morado.

---

## Slide

Crea una diapositiva.

Título: La herramienta la decide el dato, no la costumbre.

Composición: semáforo vertical de tres luces a la izquierda; a la derecha de cada luz, el tipo de información, ejemplos y la herramienta.
Filas (texto exacto: color · información · ejemplos · herramienta):
- Verde · Pública · normativa publicada, programas de otras universidades · Cualquier herramienta, incluso gratuita
- Amarillo · Interna · borradores, informes, material de curso · Cuenta institucional de Gemini
- Rojo · Sensible · notas, solicitudes, actas, datos personales · Modelo local

Pie de fuente: Ley 1581 de 2012 (protección de datos personales).
Color de acento: rojo.

## Slide

Crea una diapositiva.

Título: Si la IA puede hacer la tarea, hay que cambiar la tarea.

Composición: diagrama de una rúbrica que pasa de izquierda ("Calificar el producto") a derecha ("Calificar el proceso y el criterio"), con una flecha en el color de acento.
Rótulos (texto exacto):
- Declarar el uso de IA en trabajos y documentos
- Los detectores de texto generado no son confiables para sancionar
- Evaluar el proceso y el criterio, no solo el resultado

Color de acento: rojo.

## Slide

Crea una diapositiva.

Título: El agente actúa con nuestros permisos. La responsabilidad sigue siendo nuestra.

Composición: un agente en el centro conectado a cuatro recursos, cada uno con un candado: "Archivos", "Correo", "Comandos", "Claves".
Rótulos (texto exacto):
- Solo los permisos que la tarea necesita
- Instrucciones escondidas en documentos pueden desviar a un agente
- Las herramientas también se comprometen: en marzo de 2026 se reportó un paquete sospechoso de una librería de IA muy usada
- Lo que se firma, lo revisa una persona

Color de acento: rojo.

## Slide

Crea una diapositiva.

Título: Reglas claras para usar más, no para usar menos.

Composición: un documento grande en el centro con tres secciones visibles.
Secciones del documento (texto exacto):
- Qué herramientas, para qué datos
- Cómo se declara el uso de IA
- Quién revisa y quién firma

Color de acento: rojo.

---

## Slide

Crea una diapositiva.

Título: El siguiente paso es suyo.

Composición: tres columnas, una por público, con encabezado y una acción en letra grande.
Columnas (texto exacto):
- Estudiantes: de este vocabulario a la ingeniería de sistemas agénticos, en el curso
- Vicedecanatura: elegir el primer documento para hacerlo con agentes
- Directores de área: llevar un caso de su programa al próximo comité curricular
(Al presentar a un solo público, resaltar su columna en el color de acento y atenuar las otras dos.)

Color de acento: gris oscuro.

## Slide

Crea una diapositiva de cierre.

Título: Preguntas

Composición: título muy grande centrado; abajo, contacto y recursos en letra pequeña.
Texto (texto exacto):
- Juan David Velásquez-Henao · Facultad de Minas
- [correo de contacto]
- [enlaces a los recursos que se compartan]
Imagen: la franja de línea de tiempo completa, de "Antes de 2017" a "2026", con todas las marcas resaltadas, en la parte superior.
Color de acento: gris oscuro.

---

## Slide

Crea una diapositiva técnica de respaldo.

Título: Un LLM no busca la respuesta: calcula cuál es el siguiente token más probable.

Composición: arriba, una frase incompleta en letra grande; abajo, un gráfico de barras horizontales con las probabilidades de los candidatos; a la derecha, un ciclo pequeño.
Frase (texto exacto): La Facultad de Minas fue fundada en ___
Barras (texto exacto, de mayor a menor): "1887" 0,62 · "Medellín" 0,21 · "el" 0,09 · "1886" 0,05 · otros 0,03
Ciclo (texto exacto): Texto → tokens → probabilidades → se elige uno → se agrega y se repite
Rótulos (texto exacto):
- Atención: cada token "mira" a todos los anteriores para calcular las probabilidades
- Por eso alucina: lo más probable no siempre es lo verdadero
Nota visual: las probabilidades son ilustrativas; indícalo con un rótulo pequeño "valores ilustrativos".

Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: Un harness es un ciclo: el modelo propone, el programa ejecuta y vuelve a preguntar.

Composición: bloque de código grande a la izquierda en tipografía monoespaciada; a la derecha, tres rótulos.
Código (texto exacto):
contexto = instrucciones + documentos + objetivo
mientras no termine:
    respuesta = modelo(contexto)
    si respuesta pide una herramienta y está permitida:
        resultado = ejecutar(herramienta)
        contexto = contexto + resultado
    si no: entregar respuesta y terminar
Rótulos (texto exacto):
- El modelo solo produce texto
- El harness decide qué se ejecuta, con qué permisos y cuándo parar
- Claude Code, Codex y opencode son variaciones de este ciclo

Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: El modelo nunca ejecuta nada: escribe una solicitud, y el harness decide si la ejecuta.

Composición: secuencia vertical de cinco mensajes tipo chat, alternando a izquierda y derecha, con un rótulo de quién envía cada uno.
Mensajes (texto exacto):
1. Usuario: ¿Cuántos créditos tiene una Maestría de Profundización?
2. Modelo: {"herramienta": "buscar_normativa", "argumentos": {"tema": "créditos maestría"}}
3. Harness: ejecuta la función real y obtiene el texto del Acuerdo 033 de 2007
4. Harness → Modelo: resultado de la búsqueda
5. Modelo: Entre 50 y 75 créditos, según el Acuerdo 033 de 2007, artículo 11.
Resalta el mensaje 2 en el color de acento con el rótulo "Solo es texto en formato JSON".

Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: MCP es un protocolo cliente–servidor: el agente descubre herramientas y las invoca con mensajes estándar.

Composición: diagrama horizontal de cuatro cajas conectadas por flechas dobles; debajo, una tabla pequeña de dos filas.
Cajas (texto exacto): Host (Claude Code, Claude Desktop) ↔ Cliente MCP (uno por servidor) ↔ Servidor MCP ↔ Tools · Resources · Prompts
Rótulo sobre las flechas (texto exacto): Mensajes JSON-RPC
Tabla (texto exacto):
- stdio · el servidor corre en tu equipo, como proceso local · un solo cliente, sin red
- HTTP · el servidor corre local o remoto · varios clientes, con autenticación
Rótulo inferior (texto exacto): Cada tool habilitada describe su esquema dentro del contexto: más servidores no es gratis.

Pie de fuente: Model Context Protocol, especificación.
Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: El modelo no aprendió tus documentos: en cada pregunta le entregan los fragmentos relevantes.

Composición: dos filas de diagrama de flujo.
Fila superior, rótulo "Una vez": Documentos → Fragmentos → Embeddings → Base vectorial
Fila inferior, rótulo "En cada pregunta": Pregunta → Embedding → Fragmentos más cercanos → Contexto del modelo → Respuesta con cita
Una flecha vertical une "Base vectorial" con "Fragmentos más cercanos".
Rótulo inferior (texto exacto): Si el fragmento correcto no se recupera, el modelo no lo ve.

Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: Una skill se carga por partes: el agente solo lee lo que necesita.

Composición: diagrama de tres niveles apilados, como capas de una carpeta, con el tamaño aproximado al lado de cada uno.
Niveles (texto exacto):
1. Nombre y descripción (al inicio de SKILL.md) · siempre en el contexto · unas 100 palabras por skill
2. Cuerpo de SKILL.md: instrucciones · se carga cuando la tarea coincide con la descripción
3. Plantillas, scripts y referencias · se abren o ejecutan solo si hacen falta
Rótulo inferior (texto exacto): Por eso se pueden tener muchas skills sin saturar el contexto.

Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: Un modelo de 30 mil millones de parámetros cabe en un portátil porque cada parámetro ocupa 4 bits, no 16.

Composición: fórmula grande arriba; debajo, un gráfico de barras comparando memoria requerida contra una línea horizontal de 36 GB.
Fórmula (texto exacto): Memoria ≈ parámetros × bits por parámetro ÷ 8
Barras (texto exacto):
- 30 mil millones × 16 bits ≈ 60 GB (no cabe)
- 30 mil millones × 4 bits ≈ 15 GB (cabe, con espacio para el contexto)
- 70 mil millones × 4 bits ≈ 35 GB (al límite)
Línea horizontal rotulada: "MacBook Pro M3 Max · 36 GB"
Rótulo inferior (texto exacto): Cuantizar reduce un poco la calidad. Además del modelo, el contexto también ocupa memoria.

Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: Se paga por tokens: los que entran, los que salen y los que el modelo "piensa".

Composición: tres barras apiladas que representan una consulta, con sus partes rotuladas; a la derecha, tres rótulos.
Barra (texto exacto de sus partes): Tokens de entrada (instrucciones + documentos + pregunta) · Tokens de razonamiento · Tokens de salida (respuesta)
Rótulos (texto exacto):
- El precio se expresa por millón de tokens, y la salida cuesta más que la entrada
- Los modelos de razonamiento generan muchos tokens intermedios
- Un modelo local no cobra por token: el costo es el equipo y la energía

Color de acento: gris oscuro.

## Slide

Crea una diapositiva técnica de respaldo.

Título: La misma pregunta puede dar respuestas distintas. Por eso se verifica.

Composición: a la izquierda, tres respuestas distintas a la misma pregunta en tarjetas; a la derecha, un control deslizante rotulado "Temperatura" y tres rótulos.
Tarjetas: tres redacciones diferentes de un mismo resumen de un acta, con pequeñas variaciones.
Control deslizante (texto exacto): Baja = más predecible · Alta = más variada
Rótulos (texto exacto):
- Formato fijo para lo que procesa un programa
- Casos de prueba con criterios de aceptación
- Revisión humana de lo que se firma

Color de acento: gris oscuro.
