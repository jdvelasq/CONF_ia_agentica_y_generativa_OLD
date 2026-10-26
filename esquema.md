# IA generativa y agéntica — Esquema de contenidos

**Institución:** Facultad de Minas, Universidad Nacional de Colombia, Sede Medellín.

## Objetivo común

Antes de cualquier tema específico (los temas del curso completo aún no se han definido), la presentación construye **un vocabulario y una gramática comunes** a todos los asistentes:

- **Vocabulario:** los términos que circulan (LLM, RAG, MCP, harness, skill, "Jarvis"…), cada uno introducido en el hito donde apareció (anexo).
- **Gramática:** las estructuras que dicen cómo se combinan esos términos y permiten leer cualquier herramienta, anuncio o caso:
  1. **Las cuatro capas** (D21): ¿qué es? Modelo, harness, superficie, runtime.
  2. **El ciclo del agente** (D16): ¿cómo funciona? Objetivo → contexto → decidir → usar herramienta → observar → verificar.
  3. **Los niveles de autonomía** (D17): ¿cuánto decide solo? Asistente → flujo de trabajo → agente → agente persistente.
  4. **La escalera de uso** (D03): ¿para qué lo uso? De preguntar a delegar flujos.
  5. **La clasificación de datos** (D43, D57): ¿dónde puedo poner esta información? Público → cualquier herramienta; interno → cuenta institucional; sensible → local.

La diapositiva D29 reúne la gramática en una sola vista, al cerrar la línea de tiempo.

**Resultado esperado (prueba de que el objetivo se cumplió):** ante un anuncio nuevo, por ejemplo "una skill que permite que Claude use Perplexity internamente", el participante es capaz **por sí solo** de:

1. Ubicarlo con la gramática: qué capa es, qué modelo hay detrás, dónde quedan los datos, qué permisos pide.
2. Decidir si le sirve para su trabajo, y frente a qué alternativa.
3. Instalarlo, probarlo con información pública y desinstalarlo si no sirve.

D30 y D31 entrenan exactamente esto con ese ejemplo, y D32 lo repite con casos de la docencia diaria (por ejemplo, un MCP para hacer diagramas).

## Públicos

| Código | Público | Enfoque |
| --- | --- | --- |
| **EST** | Estudiantes de posgrado (IA generativa y agéntica para analítica) | Fundamentos técnicos, construcción de agentes, aplicación a analítica |
| **VIC** | Personal profesional de la Vicedecanatura Académica | Ventaja competitiva para la facultad, herramientas, casos operativos, uso seguro |
| **DIR** | Directores de áreas curriculares (profesores de ingeniería) | Ventaja competitiva para la facultad, casos de gestión curricular, gobernanza, decisiones |

**Niveles:** **E** = enfatizar · **M** = mencionar · **P** = pasar de largo

**Duración:** por definir. Será la que se necesite para formar la ventaja competitiva; el contenido manda y la duración se deriva de él.

**Hilo conductor para VIC y DIR:** la IA generativa y agéntica como **ventaja competitiva que proyecte a la facultad**. Las diapositivas de casos, demostración y gobernanza se presentan como piezas de esa ventaja, no como temas sueltos.

**Punto de partida de VIC y DIR:** la mayoría ha usado ChatGPT u otros asistentes de forma superficial (preguntar, redactar). La presentación los lleva de ahí al uso estratégico, apoyada en la herramienta que la universidad ya licencia: **Google Gemini para Educación** para docentes. Casos y demostración para estos públicos deben poder replicarse con esa licencia.

## Estructura narrativa

La presentación es una **línea de tiempo**, como los documentos de `agentic-playground`. Se parte de lo que la gente ha visto (ChatGPT, Gemini en Gmail, los anuncios de agentes en redes) y cada hito se asocia a una experiencia propia del público. Los términos no se explican en un glosario aparte: **cada término se introduce en la diapositiva del hito donde apareció**, cuando el público ya tiene la experiencia que lo hace necesario.

Cada diapositiva de la línea de tiempo sigue esta secuencia:

```text
fecha · hito
→ lo que la gente vio (experiencia)
→ términos que se introducen
→ qué quedó abierto → lleva al siguiente hito
```

Para EST, la presentación funciona además como puerta de entrada al curso: el bloque H muestra que el curso termina en **ingeniería de sistemas agénticos**, sin desarrollarla aquí.

Para VIC (y DIR), el destino es **construir documentos institucionales con agentes**: actualizaciones curriculares, documentos de registro calificado y procesos de acreditación, y también **evaluar propuestas**: nuevos programas, asignaturas, diplomados y cursos de extensión. El bloque I lo muestra con un caso real de la facultad.

Los riesgos también se introducen donde aparecen (alucinación con ChatGPT, permisos con computer use y con los "Jarvis"); el bloque J recoge solo la gobernanza institucional.

## Fuentes

- `/Volumes/GitHub/agentic-playground/` — cronología de hitos de IA generativa y agéntica (2017–2026), un archivo `YYMM-slug.md` por hito. Alimenta los bloques B a F.
- `/Volumes/GitHub/agentic-analytics/` — dominios de analítica de INFORMS y casos de uso de IA generativa y agéntica por actividad. Alimenta el bloque G.
- Para el bloque H: notas de cursos (`2409`, `2501`, `2509`, `2601`, `2609`, `2610-course-*`) y de diseño de skills (`2510-skill-diseno-01` a `10`) en `agentic-playground`.

---

## Matriz resumen

| # | Diapositiva | Términos que introduce | EST | VIC | DIR |
| --- | --- | --- | :-: | :-: | :-: |
| **A** | **Apertura** | | | | |
| D01 | Portada | | E | E | E |
| D02 | Lo que todos hemos visto: de ChatGPT a los anuncios de "agentes" y "Jarvis" | | E | E | E |
| D03 | ¿Dónde estoy? La escalera de uso | | M | E | E |
| **B** | **Antes de que lo viéramos (hasta 2021)** | | | | |
| D04 | Antes de 2017 · Minería de texto clásica: contar palabras no es entender | bolsa de palabras, TF-IDF, análisis de sentimiento, modelado de tópicos | E | E | E |
| D05 | 2017–2021 · Transformer, GPT-3, RAG: el autocompletar del celular, en grande | LLM, token, embeddings, RAG, modelo fundacional | E | M | E |
| **C** | **La explosión generativa (2022–2023)** | | | | |
| D06 | Nov. 2022 · ChatGPT: el día que todos lo probamos | prompt, RLHF | E | E | E |
| D07 | 2023 · Las primeras decepciones: inventa citas, no sabe lo reciente, olvida lo dicho | alucinación, fecha de corte, ventana de contexto | E | E | E |
| D08 | 2023 · La IA sale a buscar en la web: respuestas con fuentes | búsqueda web (grounding) | E | E | E |
| D09 | 2023 · ¿ChatGPT, Gemini o Claude? La carrera de modelos y los modelos abiertos | pesos abiertos, local vs. nube, fine-tuning | E | M | E |
| D10 | 2023–2024 · Ve, escucha y habla: fotos, voz y video | multimodal | M | E | M |
| **D** | **El modelo sale del chat (2023–2024)** | | | | |
| D11 | 2023 · Plugins y function calling: el modelo pide usar herramientas | tools / function calling, structured outputs, gateway | E | M | E |
| D12 | 2023–2024 · Chatear con tus documentos y que te recuerde: NotebookLM, GPTs, Gems, memoria | asistente personalizado, memoria | E | E | E |
| D13 | Sep. 2024 · "Pensando…": modelos que razonan antes de responder | modelo de razonamiento, chain-of-thought | E | M | M |
| D14 | Oct. 2024 · La IA usa el computador: el video del mouse que se mueve solo | computer use, browser use | E | E | E |
| D15 | Nov. 2024 · MCP: el enchufe universal que aparece en todos los anuncios | MCP, conector | E | E | E |
| D16 | De generar a actuar: IA generativa vs. IA agéntica | agente | E | E | E |
| D17 | Dic. 2024 · Flujos de trabajo vs. agentes: cuánta autonomía dar | flujo de trabajo, niveles de autonomía, patrones agénticos | M | E | E |
| **E** | **Agentes que trabajan (2025)** | | | | |
| D18 | Feb. 2025 · Deep Research: un informe con fuentes en minutos | deep research | M | E | E |
| D19 | La misma pregunta en Gemini: búsqueda normal vs. Deep Research | | E | E | E |
| D20 | Feb.–may. 2025 · Agentes de código: "hice una app sin saber programar" | harness, coding agent, vibe coding, hosted agent | E | E | E |
| D21 | Por qué Claude Code no es un modelo: las cuatro capas | modelo, harness, superficie, runtime | E | E | E |
| D22 | Jul. 2025 · Agentes que delegan en otros agentes | subagentes, multiagente, A2A | E | P | M |
| D23 | Sep. 2025 · Del prompt a la ingeniería de contexto | ingeniería de contexto | E | E | E |
| D24 | Oct. 2025 · Skills y plugins: empaquetar "cómo hacemos esto aquí" | skill, plugin | E | E | E |
| **F** | **Agentes para el trabajo de conocimiento (2026)** | | | | |
| D25 | 2026 · Del código a la oficina: Cowork, Workspace Agents, ChatGPT Work, Gemini en Chrome | | M | E | E |
| D26 | 2026 · Los "Jarvis": agentes personales que nunca se apagan | agente personal persistente | M | E | E |
| D27 | 2025–2026 · IA para la academia: Claude for Education, Claude for Teachers, Prism, Claude Science | | M | E | E |
| D28 | Hoy · Cómo leer un anuncio de IA sin dejarse llevar | (repaso de todos los términos) | E | E | E |
| **G** | **Leer, decidir e instalar** | | | | |
| D29 | La gramática común: cinco estructuras para leer cualquier herramienta, anuncio o caso | (reúne las estructuras) | E | E | E |
| D30 | Caso práctico: un anuncio de "una skill para que Claude use Perplexity", leído con la gramática | | E | E | E |
| D31 | Instalar sin miedo: dónde se instala cada cosa y qué revisar antes | clave de API | E | E | E |
| D32 | Para practicar: anuncios de la docencia diaria (diagramas, presentaciones, material de curso, retroalimentación) | | M | M | E |
| **H** | **IA agéntica en el ciclo de la analítica** | | | | |
| D33 | El mapa: 7 dominios + 3 transversales | | E | P | M |
| D34 | Enmarcar el problema de negocio y el problema analítico (01, 02) | | E | P | P |
| D35 | Datos (03) | | E | P | P |
| D36 | Metodología y modelado (04, 05) | | E | P | P |
| D37 | Despliegue y gestión del ciclo de vida (06, 07) | | E | P | P |
| D38 | Ingeniería: DataOps, MLOps y código limpio (08–10) | | E | P | P |
| **I** | **El curso: hacia la ingeniería de sistemas agénticos** | | | | |
| D39 | 2024–2026 · La ingeniería de agentes se vuelve disciplina universitaria: Berkeley, Stanford, CMU… y la Facultad de Minas | ingeniería de sistemas agénticos | E | M | E |
| D40 | Lo que viene en el curso: de este vocabulario común a la ingeniería de sistemas agénticos | | E | P | M |
| **J** | **IA en la gestión académica: hacia documentos institucionales construidos con agentes** | | | | |
| D41 | La herramienta que ya tenemos: exactamente qué hace Gemini para Educación | | M | E | E |
| D42 | Más allá de Gemini: Perplexity, Claude, ChatGPT/Codex y DeepSeek, qué hace mejor cada uno y qué se puede hacer gratis | | E | E | E |
| D43 | Cuando los datos no pueden salir: modelos locales | | E | E | E |
| D44 | Casos: Vicedecanatura Académica | | P | E | M |
| D45 | Casos: dirección de áreas curriculares | | P | M | E |
| D46 | Caso real: la actualización curricular de la Maestría en Ingeniería – Analítica, construida con un agente | | M | E | E |
| D47 | Cómo se hizo: los conceptos de la línea de tiempo en acción | observabilidad | M | E | E |
| D48 | Qué hizo el agente y qué decidió la persona | | M | E | E |
| D49 | El mismo patrón para acreditación, registro calificado y autoevaluación | | P | E | E |
| D50 | Evaluar propuestas: nuevos programas, asignaturas, diplomados y cursos de extensión | evals, LLM como juez | P | E | E |
| D51 | Demostración en vivo: una sección construida con el patrón | | E | E | E |
| **K** | **Ventaja competitiva para la facultad** | | | | |
| D52 | La ventana de oportunidad: por qué la ventaja es de quien llega primero | | M | E | E |
| D53 | Tres frentes de ventaja: oferta académica, operación académica, proyección externa | | P | E | E |
| D54 | Lo que ya tenemos: capacidades diferenciales de la facultad | | M | E | E |
| D55 | Hoja de ruta: de pilotos a capacidad institucional | | P | E | E |
| D56 | Cómo medir el avance | | P | M | E |
| **L** | **Gobernanza** | | | | |
| D57 | Privacidad y datos institucionales | | M | E | E |
| D58 | Integridad académica y evaluación | | E | M | E |
| D59 | Supervisión humana, permisos y seguridad | | M | E | E |
| D60 | Lineamientos institucionales de uso | | P | E | E |
| **M** | **Cierre** | | | | |
| D61 | Próximos pasos | | E | E | E |
| D62 | Recursos y preguntas | | E | E | E |
| **N** | **Respaldo técnico (se muestra si preguntan)** | | | | |
| D63 | Cómo predice un LLM: tokens, probabilidades y atención | | M | P | M |
| D64 | Por dentro de un harness: el ciclo en seis líneas de pseudocódigo | | M | P | M |
| D65 | Qué pasa realmente en una llamada a una tool | | M | P | M |
| D66 | Cómo funciona MCP por dentro | | M | P | M |
| D67 | Cómo funciona RAG por dentro | | M | P | M |
| D68 | Anatomía de una skill: carga progresiva | | M | P | M |
| D69 | Por qué un modelo de 30 mil millones de parámetros cabe en un portátil | | M | P | M |
| D70 | Cuánto cuesta: tokens de entrada, de salida y de razonamiento | | M | P | M |
| D71 | ¿Es determinista? Temperatura, variabilidad y verificación | | M | P | M |

---

## Detalle por diapositiva

Está en `slides.md`: cada sección es una instrucción autocontenida para pegar en Claude o Codex para PowerPoint (título, composición, imagen, texto exacto, recuadro de términos, pie de fuente y color de acento), precedida de una sección ESTILO que se pega una vez por sesión. Este archivo conserva el plan, los públicos y los insumos; los niveles por público y los pendientes viven solo aquí.

## Curiosidad anticipada (DIR: profesores de ingeniería)

Los directores son ingenieros: después de cada "qué" van a preguntar "cómo funciona" y "cuánto cuesta". Estas son las preguntas más probables, la diapositiva donde surgen y la de respaldo que las responde (bloque N). Al presentar a DIR, invitar explícitamente a preguntar por dentro.

| Surge en | Pregunta probable | Respaldo |
| :-: | --- | :-: |
| D05, D07 | ¿Cómo "sabe" un LLM? ¿Por qué inventa con tanta seguridad? | D63 |
| D16, D20, D21 | ¿Qué es un harness en términos de software? ¿Qué hace que no haga el modelo? | D64 |
| D11 | ¿El modelo ejecuta código? ¿Quién controla lo que se ejecuta? | D65 |
| D15, D30 | ¿Qué protocolo usa MCP? ¿Corre local o remoto? ¿Cuánto contexto consume? | D66 |
| D12, D46 | ¿El modelo "aprendió" mis documentos? ¿Cómo encuentra el fragmento correcto? | D67 |
| D24, D31 | ¿Qué hay dentro de una skill? ¿Por qué no satura el contexto tener muchas? | D68 |
| D43 | ¿Cómo cabe un modelo tan grande en 36 GB? ¿Qué se pierde? | D69 |
| D42, D55 | ¿Cuánto cuesta usar esto a escala? ¿Por qué el razonamiento es más caro? | D70 |
| D47, D50 | ¿Da siempre la misma respuesta? ¿Cómo se valida algo no determinista? | D71 |

## Pendientes antes de presentar

- **D41:** edición de Google Workspace for Education y complementos que tiene la UNAL; si los estudiantes también tienen acceso.
- **D42:** acuerdos institucionales de la UNAL con Perplexity, Anthropic u OpenAI; límites vigentes de las versiones gratuitas (las cifras actuales vienen de sitios de terceros).
- **D31:** nombres exactos de los menús de la app de Claude para subir skills y qué planes lo permiten.
- **D32:** disponibilidad vigente de cada herramienta; el MCP de Excalidraw no se confirmó como oficial y quedó fuera.
- **D43:** si la facultad tiene equipos o servidores con GPU; instalar Ollama y un modelo en el equipo del profesor para la demostración.
- **D44, D45:** validar los casos con la Vicedecanatura y con los directores de área.
- **D50:** rúbricas o formatos de evaluación de propuestas que ya tenga la facultad.
- **D51:** tarea concreta y herramienta de la demostración (candidata: instalar el conector oficial de Perplexity en Claude Code, consultar y desinstalar).
- **D55, D56:** horizontes de la hoja de ruta e indicadores, por acordar con la Vicedecanatura.
- **D60:** lineamientos de uso de IA que ya tengan la UNAL o la facultad.
- **D40:** programa del curso (temas intermedios aún no definidos).
- **D62:** correo de contacto y recursos que se compartirán públicamente.
- **Recuadros "Pruébelo":** ensayar cada instrucción en la herramienta indicada antes de presentar (en especial D14 con un agente de navegador sobre el SNIES, D25 con Claude Cowork y D09 con Ollama), y ajustar el texto a lo que realmente funcione.
- **Bloque N (respaldo técnico):** las probabilidades de D63 son ilustrativas; las cifras de memoria de D69 son aproximadas.

---

## Insumos para D03 (la escalera de uso)

De abajo hacia arriba; la mayoría de VIC y DIR está en los peldaños 1–2. Cada peldaño se ilustra con Gemini institucional y remite al hito de la línea de tiempo donde apareció.

1. **Preguntar:** usar el chat como buscador mejorado (D06).
2. **Redactar y resumir:** correos, actas, comunicaciones (D06).
3. **Trabajar con documentos propios:** cargar normativa, acuerdos o programas y preguntar con citas en Gemini Notebook, antes NotebookLM (D12).
4. **Instrucciones reutilizables:** asistentes configurados para una tarea recurrente, como los Gems (D12).
5. **Investigar:** búsqueda y lectura en varias rondas con informe y fuentes en Deep Research (D18).
6. **Delegar flujos:** agentes que ejecutan tareas de varios pasos sobre correo, documentos y hojas de cálculo (D25).

## Insumos para D41 (exactamente qué hace Gemini para Educación)

Verificado en fuentes oficiales de Google (octubre de 2026). **Lo que se puede hacer depende de la edición que tenga la universidad**, así que antes de presentar hay que confirmar con la UNAL qué edición y qué complementos tiene.

| Función | Education Fundamentals (sin costo) | Education Plus | Complemento Google AI Pro for Education |
| --- | :-: | :-: | :-: |
| App Gemini (chat, Gems, Deep Research, Canvas) | Sí, con límites de uso | Sí, con límites de uso | Límites ampliados y modelos premium |
| Gemini Notebook (antes NotebookLM): respuestas basadas solo en las fuentes cargadas, resúmenes en audio y video, infografías, presentaciones | Sí, con topes diarios | Topes más altos | Topes más altos |
| Gemini dentro de Docs, Sheets, Slides, Forms y Vids | No | Sí | Sí |
| Gemini dentro de Gmail, Meet, Drive y Chat | No | No | Sí |

- **Protección de datos:** con la cuenta institucional, la app Gemini y Gemini Notebook son servicios principales bajo los términos de Workspace for Education; según Google, los datos **no son revisados por personas ni se usan para entrenar modelos**. Esta protección no aplica a cuentas personales de Google.
- **Administración:** la universidad puede habilitar o restringir el acceso por grupos o unidades organizacionales.
- **Agentes de Google más allá del chat:** Gemini CLI (D20) y Google Antigravity. _Por verificar:_ si se pueden usar con la cuenta institucional.
- _Por verificar con la UNAL:_ edición contratada, complementos, si los estudiantes también tienen acceso, y si hay lineamientos internos de uso.
- Mensaje para D57 (privacidad): los datos institucionales van en la cuenta institucional, no en cuentas personales de ChatGPT u otros.

Fuentes: Google Workspace, _Quickstart Guide to Gemini and Gemini Notebook for Education_; Google for Education, _Compare Editions_.

## Insumos para D42 (qué hace mejor cada herramienta)

Mensaje central: **Gemini es la base institucional, no la única herramienta.** Cada una tiene una ventaja distinta; la regla que decide cuál usar es qué datos se van a poner en ella.

| Herramienta | En qué se destaca | Cuándo conviene | Cuidado con |
| --- | --- | --- | --- |
| **Gemini (institucional)** | Integración con Gmail, Drive y Docs; Gemini Notebook para trabajar con normativa y documentos propios; protección de datos de la licencia | Todo lo que involucre datos institucionales | Las funciones dependen de la edición contratada (D41) |
| **Perplexity** | Búsqueda en la web con fuentes citadas en cada afirmación; información reciente | Vigilancia de competidores, tendencias, normativa nueva, programas de referencia | Verificar las fuentes; sin acuerdo institucional, no subir documentos internos |
| **Claude** | Redacción larga y matizada; documentos extensos; Claude para Excel, PowerPoint y Word; Cowork para delegar tareas de oficina; Claude Code, con el que se construyó el caso de D46 | Documentos institucionales, análisis de documentos largos, flujos agénticos completos | Sin acuerdo institucional, cuidar qué datos se suben |
| **ChatGPT / Codex** | La herramienta más conocida; GPTs, Deep Research, ChatGPT Agent; Codex como agente de código y de documentos | Prototipos rápidos, automatización, alternativa a Claude Code | Igual que Claude |
| **DeepSeek** (y otros modelos abiertos como Qwen, Kimi o GLM) | Pesos abiertos con licencia permisiva; razonamiento competitivo a muy bajo costo; versiones pequeñas que corren en un computador propio | Ejecutar un modelo **localmente**, sin que los datos salgan del equipo; docencia e investigación | Su app y API oficiales procesan los datos en servidores en China, y varios gobiernos restringieron su app en dispositivos oficiales en 2025. Para datos institucionales, solo en ejecución local |

- Conecta con D09 (pesos abiertos, local vs. nube) y D21 (las cuatro capas): DeepSeek es a la vez un modelo descargable y un servicio en la nube, y el riesgo depende de cuál de los dos se use.
- _Por verificar antes de presentar:_ si la UNAL tiene acuerdos institucionales con Perplexity, Anthropic u OpenAI; condiciones de privacidad vigentes de cada herramienta.

### Lo que se puede hacer gratis

Todas tienen una versión gratuita útil para probar y para trabajar con información pública. Los límites cambian con frecuencia y las fuentes no coinciden en las cifras exactas: verificar en la página oficial de cada una antes de presentar.

| Herramienta | Versión gratuita (octubre de 2026, aproximado) | Lo que queda fuera o muy limitado |
| --- | --- | --- |
| **Gemini** (cuenta personal de Google) | Chat, Gems, Gemini Notebook, Deep Research con límites; **Gemini CLI** gratuito como agente de terminal | Límites de uso más bajos que la licencia institucional; sin la protección de datos de Workspace for Education |
| **Perplexity** | Búsquedas básicas con fuentes prácticamente ilimitadas; unas 3 búsquedas avanzadas al día; Deep Research muy limitado | Búsquedas avanzadas y Deep Research a escala |
| **Claude** | Chat con el modelo intermedio, hasta 5 proyectos con documentos propios, carga de archivos, búsqueda web, Artifacts, memoria; límite de uso por ventana de 5 horas | Claude Code, Cowork, Research y el modelo más potente |
| **ChatGPT / Codex** | Chat de uso diario, pocas cargas de archivos al día, Deep Research y Codex en versión limitada | GPTs y proyectos propios, uso intensivo de Deep Research y Codex |
| **DeepSeek, Qwen, Kimi** | Chat web gratuito; modelos descargables gratis para ejecución local (por ejemplo, con Ollama) | Nada relevante en funciones; la limitación es dónde quedan los datos |

**Regla para versiones gratuitas personales:** en general, el proveedor puede usar las conversaciones para entrenar modelos o revisarlas, salvo que la persona lo desactive en la configuración. Sirven para información pública (normativa publicada, tendencias, programas de otras universidades), **nunca para datos institucionales** (estudiantes, notas, actas, documentos internos). Para esos datos: Gemini con la cuenta institucional o un modelo local.

Fuentes de los límites gratuitos: sitios de terceros (Fast.io, DataStudios, AI-Toolbox, FelloAI, ToolColumn), no páginas oficiales; tratarlos como aproximados.

## Insumos para D43 (modelos locales)

Mensaje central: **hay información de la facultad que no debería salir de sus equipos**, y hoy es posible procesarla con IA sin enviarla a ningún proveedor. Retoma la pregunta transversal de `agentic-playground`: ¿hasta dónde se pueden llevar las capacidades de IA ejecutándolas en una máquina propia?

**Qué motiva lo local en la gestión académica:**

- Datos personales de estudiantes y profesores, protegidos por la Ley 1581 de 2012 (habeas data): historias académicas, notas, solicitudes, situaciones de salud o socioeconómicas.
- Actas de consejos y comités, casos disciplinarios, evaluaciones docentes.
- Propuestas de programas o asignaturas aún no aprobadas, investigación inédita, información de convenios: propiedad intelectual y confidencialidad.
- Independencia del proveedor: las condiciones de las versiones gratuitas cambian, y algunos servicios procesan los datos en otras jurisdicciones (D42, DeepSeek).

**Qué se puede hacer hoy en local** (ejemplos de `agentic-playground` y `agentic-analytics`, con su hito):

| Necesidad | Herramienta local | Hito |
| --- | --- | :-: |
| Chatear con un modelo, como ChatGPT pero en el equipo | Ollama + Open WebUI, o LM Studio | D09 |
| Preguntar sobre documentos propios con citas (actas, normativa, solicitudes) | AnythingLLM con workspaces y embeddings locales | D12 |
| Convertir PDF, Word o escaneos en texto estructurado sin subirlos | Docling | D12 |
| Transcribir grabaciones de reuniones o comités | Whisper (MLX Whisper en Mac) | D10 |
| Agente que trabaja sobre archivos y documentos | opencode u OpenHands con un modelo local | D20 |
| Modelos que razonan, descargables | gpt-oss, Qwen, Gemma, versiones pequeñas de DeepSeek-R1 | D09, D13 |

**El hardware no es un servidor especial: es un portátil de gama alta.** Referencia real: este esquema se está construyendo en una MacBook Pro M3 Max con 36 GB de memoria. En los Mac con chip Apple Silicon la memoria es compartida entre CPU y GPU, de modo que casi toda sirve para cargar el modelo.

| Memoria del equipo | Qué corre con comodidad (modelos cuantizados a 4 bits) | Uso típico |
| --- | --- | --- |
| 16 GB | Modelos de 7–8 mil millones de parámetros; Whisper | Resumir, redactar, transcribir |
| 32–36 GB | Modelos de hasta unos 30 mil millones de parámetros (por ejemplo gpt-oss-20b, Gemma de 27B, Qwen de 30B, DeepSeek-R1 de 32B) | Trabajo con documentos propios, razonamiento, agentes locales |
| 64–128 GB | Modelos de 70 mil millones de parámetros o más | Calidad cercana a los modelos en la nube; servidor compartido para una dependencia |

- **Opción de compra:** MacBook Pro o Mac Studio con chip M y 36 GB o más de memoria, o equipos equivalentes con GPU de NVIDIA. Un equipo por dependencia (Vicedecanatura, cada área curricular) o uno compartido que sirva a varias personas por la red interna.
- _Por definir en la demostración:_ instalar Ollama y un modelo en el equipo del profesor y mostrar en vivo una tarea con datos sensibles sin conexión a internet (actualmente no hay modelos locales instalados en ese equipo).

**Lo que se pierde:** calidad menor que los modelos más avanzados en la nube, sobre todo con modelos pequeños; no busca en la web por defecto; alguien debe instalar y mantener.

**Arquitectura híbrida recomendada:** datos sensibles en local o en la cuenta institucional; información pública en la nube con la mejor herramienta disponible (D42).

**Conexión con la ventaja competitiva:** equipos de IA local en las dependencias de la facultad, con una guía para instalarlos y usarlos, es una capacidad que pocas instituciones tienen y con una inversión acotada (portátiles, no centros de datos). Llevarlo a la hoja de ruta (D55).

## Insumos para D46–D51 (documentos institucionales con agentes)

Fuente: repositorio `github.com/jdvelasq/maestria-en-analitica`.

**D46 · El caso.** Documento de actualización curricular de la Maestría en Ingeniería – Analítica: 25 secciones fijas exigidas por la Vicerrectoría Académica (justificación, prospectiva, estado actual, tendencias, políticas, objetivos, perfil, competencias, resultados de aprendizaje, plan de estudios, malla, evaluación, plan de transición…), un archivo por sección. A partir de un borrador inicial, el agente distribuyó, completó y consolidó el documento en una sola jornada (16 versiones registradas el 20 de octubre de 2026).

**D47 · Cómo se hizo, con los términos de la línea de tiempo:**

| Lo que se hizo | Concepto | Hito |
| --- | --- | :-: |
| Un archivo de instrucciones (`AGENTS.md`) con objetivo, alcance, fuentes, reglas y decisiones ya tomadas | Ingeniería de contexto, memoria | D23, D12 |
| Normativa (Acuerdo 02/2020 del CESU, Acuerdo 033/2007 del CSU, lineamientos de armonización curricular) como documentos fuente | Trabajar con documentos propios (RAG) | D05, D12 |
| Búsqueda web de competidores, precedentes regulatorios y programas internacionales | Deep research | D18 |
| Cada cifra con fuente y año; no repetir mercadeo de competidores sin verificar | Control de alucinaciones | D07 |
| Reglas fijas: terminología, registro académico, "un archivo, una sección", no copiar texto literal | Skill (conocimiento de "cómo hacemos esto aquí") | D24 |
| Cada cambio queda versionado y se puede revisar o revertir | Observabilidad, trazabilidad | D47 (se introduce aquí) |

**D48 · Qué hizo el agente y qué decidió la persona.** Ejemplos reales del caso:

- El agente detectó que una propuesta de créditos dejaba el Trabajo Final en 22,7 %, por encima del máximo de 20 % del Acuerdo 033/2007, y lo reportó **antes** de aplicar el cambio; la persona decidió cómo resolverlo.
- La persona fijó la estructura de créditos (40 por plan) tras varias iteraciones; el agente la propagó de forma consistente a las secciones 16, 17 y 22.
- Una verificación corrigió la narrativa competitiva: la Especialización en Analítica (2014) es anterior a casi toda la oferta nacional, de modo que la facultad no es un entrante tardío.
- Lo que el agente no decide: cuáles tres asignaturas conforman el plan de investigación queda explícitamente para el comité asesor.

**D49 · El mismo patrón para acreditación.** Fuentes normativas + evidencia (cifras de matrícula, egresados, profesores, investigación) + reglas de redacción + secciones fijas + revisión humana. Aplica a autoevaluación con fines de acreditación (factores del Acuerdo 02/2020 del CESU), renovación de registro calificado, informes de gestión y planes de mejoramiento.

**D50 · Evaluar propuestas, no solo producir documentos.** El mismo patrón, invertido: el agente revisa una propuesta contra criterios explícitos y entrega un informe con evidencia; la decisión sigue en el comité o consejo correspondiente.

- **Qué se evalúa:** ideas de nuevos programas, asignaturas propuestas, diplomados y cursos de extensión.
- **Criterios posibles:** cumplimiento normativo (créditos, horas, requisitos); pertinencia (evidencia de mercado y política pública); coherencia con los resultados de aprendizaje y el perfil del programa; duplicidad o articulación con la oferta existente de la facultad; viabilidad (profesores, recursos, demanda).
- **Términos que reaparecen:** evals y LLM como juez (se introducen aquí), producir y revisar por separado (la revisión no la hace el mismo agente que redactó), supervisión humana (D59).
- _Por definir:_ si la facultad ya tiene rúbricas o formatos de evaluación para cada tipo de propuesta; serían el insumo central.

**D51 · Demostración.** Construir o revisar en vivo una sección con el patrón.

_Por decidir:_ el caso se construyó con un agente de código sobre un repositorio, no con Gemini. Hay que definir qué parte del patrón se replica con la licencia de Gemini (Gemini Notebook con la normativa, Gems con las reglas, Deep Research para la evidencia) y qué parte requiere un agente como Claude Code, Codex o Gemini CLI.

## Insumos para D54 (lo que ya tenemos)

- **Liderazgo docente propio en analítica e IA:** el profesor de las asignaturas de analítica de la facultad propuso la asignatura _IA generativa y agéntica para analítica_ y la dictará. La facultad no depende de traer el conocimiento de afuera.
- **Conocimiento ya sistematizado:** cronología de hitos 2017–2026 (`agentic-playground`) y casos de uso de IA por dominio de analítica de INFORMS (`agentic-analytics`), ambos elaborados por el mismo profesor.
- **La facultad en la misma conversación que Berkeley, Stanford y CMU:** esas universidades abrieron cursos de agentes entre 2024 y 2026; la Facultad de Minas tiene el suyo, orientado a analítica (D39).
- **Licencia institucional de Google Gemini para Educación** para docentes: la herramienta ya está pagada y disponible; la ventaja no está en tenerla, sino en usarla a fondo.
- **Trayectoria pionera en analítica:** la Especialización en Analítica de la facultad se creó en 2014, antes que casi toda la oferta de posgrado en analítica del país; la Maestría en Ingeniería – Analítica se creó en 2017 (Acuerdo 262 del CSU) y abrió en 2018.
- **Propuestas curriculares en curso con IA agéntica en el núcleo:** la actualización de la Maestría en Analítica y una propuesta hermana de Especialización en Ingeniería de Software Agéntica (Departamento de Ciencias de la Computación y de la Decisión). La asignatura de IA generativa y agéntica figura como _propuesta_ en la actualización; presentarla así.
- **Un caso real de documento institucional construido con agentes** (D46).
- _Por confirmar:_ grupos de investigación, infraestructura de cómputo, alianzas.

---

## Anexo: términos y dónde se introducen

Este es el **vocabulario común** (ver "Objetivo común"). Definiciones de una línea para redactar cada diapositiva. No es un bloque de la presentación: cada término vive en la diapositiva indicada.

| Término | Diapositiva | Definición |
| --- | :-: | --- |
| Bolsa de palabras | D04 | Representar un texto por las palabras que contiene y cuántas veces aparecen, sin importar el orden. |
| TF-IDF | D04 | Peso de una palabra: alto si es frecuente en un documento y rara en el resto; base de buscadores y clasificadores clásicos. |
| Análisis de sentimiento | D04 | Clasificar un texto como positivo, negativo o neutro; en la versión clásica, con diccionarios de palabras o un clasificador entrenado con ejemplos etiquetados. |
| Modelado de tópicos | D04 | Descubrir temas en una colección de documentos a partir de qué palabras aparecen juntas (LDA, 2003). |
| LLM | D05 | Modelo de lenguaje grande; genera texto prediciendo el siguiente fragmento. |
| Token | D05 | Fragmento de texto con el que el modelo lee, escribe y se cobra. |
| Embeddings | D05 | Representación numérica del significado de un texto; permite buscar por sentido y no por palabras exactas. |
| RAG | D05 | Buscar en documentos propios y entregarle al modelo los fragmentos relevantes para que responda con base en ellos. Reaparece en D12 como experiencia ("chatear con tus documentos"). |
| Modelo fundacional | D05 | Modelo entrenado una vez con datos masivos que sirve de base para muchas tareas. |
| Prompt | D06 | La instrucción que se le da al modelo. |
| RLHF | D06 | Entrenamiento con retroalimentación humana; es lo que hace que el modelo siga instrucciones y converse. |
| Alucinación | D07 | Respuesta plausible y bien redactada, pero falsa. |
| Fecha de corte | D07 | Hasta cuándo llegan los datos con que se entrenó el modelo; después de esa fecha no sabe nada sin buscar. |
| Ventana de contexto | D07 | Cuánto texto puede tener en cuenta el modelo a la vez. |
| Búsqueda web (grounding) | D08 | El modelo busca en internet antes de responder y ancla la respuesta en las fuentes que encontró, con enlaces para verificar. |
| Pesos abiertos | D09 | El modelo se puede descargar y ejecutar en máquina propia (Llama, Qwen, Gemma, gpt-oss). |
| Local vs. nube | D09 | Dónde se ejecuta el modelo; en local los datos no salen del equipo. |
| Fine-tuning / LoRA | D09 | Ajustar un modelo existente con datos propios. |
| Multimodal | D10 | Entiende o genera texto, imagen, audio y video. |
| Tools / function calling | D11 | El modelo pide ejecutar una función (buscar, leer un archivo, consultar una base de datos) y recibe el resultado. |
| Gateway / router de modelos | D11 | Intermediario que permite usar muchos modelos y proveedores con una sola interfaz (OpenRouter, LiteLLM). |
| Structured outputs | D11 | (Ago. 2024) El modelo responde con datos en un formato fijo (JSON) que un programa puede leer sin errores. |
| Asistente personalizado | D12 | Instrucciones y archivos guardados para una tarea recurrente (GPTs, Gems). |
| Memoria | D12 | Lo que el sistema recuerda de una conversación a otra. |
| Modelo de razonamiento | D13 | Dedica tiempo a "pensar" antes de responder; mejor en problemas difíciles, más lento y costoso. |
| Chain-of-thought | D13 | Razonar paso a paso antes de dar la respuesta. |
| Computer use / browser use | D14 | El agente opera la pantalla o el navegador como lo haría una persona. |
| MCP | D15 | Estándar abierto para conectar cualquier agente con herramientas y fuentes de datos; una integración escrita una vez sirve para todos los agentes compatibles. |
| Conector | D15 | Integración lista para un servicio concreto (correo, calendario, Drive, SharePoint). |
| Agente | D16 | Un modelo que, en ciclo, decide qué herramienta usar, observa el resultado y sigue hasta cumplir un objetivo. |
| Flujo de trabajo | D17 | Los pasos los define una persona; el modelo ejecuta cada paso. En un agente, el modelo decide el camino. |
| Patrones agénticos | D17 | Formas recurrentes de organizar modelos y herramientas: encadenar, enrutar, paralelizar, orquestar trabajadores, evaluar y corregir. |
| Deep research | D18 | Agente que investiga en varias rondas de búsqueda y lectura y entrega un informe con fuentes. |
| Harness | D20 | El programa que envuelve al modelo y lo pone a trabajar en un ciclo con contexto, herramientas, permisos y revisión (Claude Code, Codex, opencode, Cowork). |
| Coding agent | D20 | Agente que lee, modifica y ejecuta código en un proyecto, normalmente desde la terminal. |
| Vibe coding | D20 | Construir software describiendo lo que se quiere y aceptando lo que funciona, sin revisar el código en detalle. |
| Hosted agent | D20 | Agente que corre en los servidores del proveedor, no en el equipo propio. |
| Las cuatro capas | D21 | **Modelo** (predice y genera), **harness** (lo pone a trabajar), **superficie** (por dónde se opera: chat, terminal, IDE, Office), **runtime** (dónde corre: nube, local, gateway). Un producto mezcla capas: no confundirlo con el modelo que usa. |
| Subagentes / multiagente | D22 | Un agente reparte partes de la tarea entre otros agentes. |
| A2A | D22 | Protocolo para que agentes de distintos proveedores se comuniquen y deleguen tareas entre sí. |
| Ingeniería de contexto | D23 | Diseñar toda la información que recibe el modelo (instrucciones, documentos, herramientas, historial), no solo la pregunta. |
| Skill | D24 | Carpeta con instrucciones, scripts y recursos que el agente carga solo cuando la tarea lo requiere; empaqueta "cómo hacemos esto aquí". |
| Plugin | D24 | Paquete que agrega skills, comandos o conexiones MCP a un harness. |
| Agente personal persistente ("Jarvis") | D26 | Corre todo el tiempo, tiene memoria e identidad propias, accede a correo, mensajería, calendario y archivos, y puede actuar por iniciativa propia. Abiertos: OpenClaw, Hermes Agent, OpenJarvis. Operados por el proveedor: Gemini Spark, Microsoft Autopilot, OpenAI dots, Meta Muse. |
| Clave de API | D31 | Credencial con la que un programa usa un servicio en nombre de alguien y que registra el consumo para cobrarlo; no es lo mismo que la suscripción al chat del servicio. |
| Ingeniería de sistemas agénticos | D39 | Disciplina que diseña, construye, evalúa y opera sistemas basados en agentes con el rigor de cualquier sistema de software en producción. |
| Observabilidad | D47 | Dejar registro (trazas, logs, costos, decisiones) para reconstruir qué hizo un agente y por qué. |
| LLM como juez | D50 | Usar un modelo para evaluar las respuestas de otro según criterios definidos. |
| Evals | D50 | Conjunto de casos de prueba con criterios de aceptación para medir si un sistema basado en LLM funciona y no empeora entre versiones. |

### Preguntas para D28 (cómo leer un anuncio)

1. ¿Qué capa es: modelo, harness, superficie, runtime o integración?
2. ¿Qué modelo usa por debajo y quién lo provee?
3. ¿Dónde quedan los datos: en el equipo, en la nube institucional o en el proveedor?
4. ¿Qué permisos pide: leer archivos, enviar correos, ejecutar comandos?
5. ¿Es producto estable, vista previa o demo? ¿Hay una fuente primaria?
6. ¿Qué problema concreto de mi trabajo resuelve?
