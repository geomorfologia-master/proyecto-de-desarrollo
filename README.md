Proyecto de desarrollo. Tu tema, tu
investigación<small><br>Geomorfología (GEO-114)<br>Universidad Autónoma
de Santo Domingo (UASD)<br>Semestre 2024-02</small>
================
El Tali
2024-10-22

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

Versión HTML (quizá más legible),
[aquí](https://geomorfologia-master.github.io/proyecto-de-desarrollo/README.html)

# Fecha/hora de entrega

**Último día de clases, semestre 2024-02, 11:59 pm.**

# Objetivos

Vas a realizar un estudio reproducible con datos preexistentes o datos
que generarás tu mismo/a con los objetivos siguientes:

1.  Incorporar o mejorar tus habilidades para formular un diseño
    observacional o experimental.

2.  Mejorar tus capacidades de toma de datos.

3.  Incorporar técnicas analíticas para análisis de datos.

4.  Mejorar tus habilidades de uso de software de procesamiento de texto
    incorporando citas, referencias, referencias cruzadas, apoyo gráfico
    y tablas.

5.  Mejorar tus capacidades de redacción en un entorno de programación.
    Esto te preparará, a futuro, para redactar resultados reproducibles.

Este proyecto de desarrollo tratará **el tema que elijas o te ayuden a
elegir**, restringido a cualquiera de los tópicos impartidos durante el
semestre, usando una o varias técnicas impartidas, usando datos ya
disponibles o que puedas colectar por tu cuenta, e intentando que sea
una investigación reproducible y bien redactada (nada de alto nivel,
pero suficientemente presentable; recuerda: quedará en GitHub, así que
“sonría, le filmamos”). El objetivo principal es que produzcas un
estudio reproducible que constituya una aportación nueva al conocimiento
y que, a la vez cumpla, con estilos de formato, uso apropiado de
figuras, tablas, citas y referencias.

# Mandato

Redacta un manuscrito, basándote en la plantilla `manuscrito.Rmd` que se
encuentra en este mismo repositorio. Para hacerlo, deberás clonar este
repositorio, muy parecido a como hiciste con la PD01 y en la PD02. Para
ello, ve al [portal de la
asignatura](https://github.com/geomorfologia-202402), haz clic en el
enlace de asignación “Proyecto de desarrollo. Tu tema, tu investigación”
y acepta la asignación.

## Instrucciones

Como ya viene siendo habitual, deberás usar estilos de formato (los
títulos debidamente escritos, el texto normal también, siguiendo lo
aprendido en la PD01 y en la PD02), y tendrás que incorporar referencias
bibliográficas, referencias cruzadas a figuras y tablas (es decir,
necesitarás que las figuras y tablas tengan título o “*caption*”). No
podrás desarrollar tu redacción usando listas de viñetas ni listas
numeradas. Recuerda usar la plantilla mencionada. Distribuye tu texto en
las siguientes secciones:

- **Introducción** (tamaño mínimo: 4 párrafos). Desde lo amplio,
  comienza escribiendo sobre tu tema de investigación (de qué temática
  trata). A continuación, explica acota tu tema específico, explicando
  por qué es necesario el estudio, para qué podrían usarse los
  resultados. Plantea tu o tus objetivos, preguntas de investigación e
  hipótesis. Cierra con la importancia que reviste tu tema estudiado
  respecto del conjunto de la ciencia.

  - Dentro de esta sección, debes incluir tantas citas como sean
    necesarias, con un mínimo de 10. Los conceptos y afirmaciones
    ajenas, deben citarse bibliográficamente, y nunca deberás usar cita
    literal, pues se considera plagio. Las citas bibliográficas que
    incluyas, deberán estar respaldadas por sus correspondientes cuyas
    referencias, que deberán aparecer en la sección final (Referencias).
    Las citas y la lista de referencias, deberán seguir el estándar APA
    7ma edición (APA7), que es el que la propia plantilla tiene
    configurado por defecto; en principio, no tendrás que ocuparte de
    todos los detalles de sintaxis del formato APA7, pero no debes
    confiar ciegamente en lo que hace RMarkdown.

  - En esta sección (o en la siguiente de “Materiales y métodos”) debes
    incluir la descripción del ámbito geográfico del estudio, ya sea
    dentro de un subtítulo o como párrafo debidamente integrado en el
    texto donde lo insertes. Con independencia de dónde lo incluyas, lo
    importante es que no omitas dicho texto. En un manuscrito del área
    de \*geografía, no puede omitirse la descripción del área o
    territorio estudiado.

- **Materiales y métodos** (tamaño mínimo: 4 párrafos). Explica,
  restringiéndote a tus objetivos y/o preguntas de investigación, cómo
  estableciste el diseño de muestreo (si aplica) y/o cómo obtuviste los
  datos que usaste, la fecha de producción o colecta de los mismos, qué
  fórmulas usaste, cómo configuraste los algoritmos o el software
  empleado. Es decir, debes documentar tus fuentes y herramientas.
  También, cita el software y el hardware usados (que son a fin de
  cuentas los “materiales”), e igualmente cita las técnicas y/o
  algoritmos empleados. Importante: **debes incluir al menos diez citas
  en esta sección** (“y poco me lo jayo”, pues normalmente usamos
  muchísimas herramientas que no citamos). Si incluyes un diagrama de
  flujo metodológico (en algunas revistas le llaman “metodología
  gráfica”), te resultará más fácil explicar los pasos dados, y podrás
  visibilizar mejor tanto las entradas de datos como las salidas de
  información. **No adelantes resultados en esta sección, restringe tu
  redacción a responder la pregunta “cómo y con qué hice lo que hice”,
  es decir, tu diseño de muestreo (si aplica), tus fuentes y tus
  herramientas, las fórmulas que empleaste, y qué técnicas concretas o
  algoritmos utilizaste (métodos)**. Toda figura y tabla que insertes
  debe citarse con referencia cruzada. Para construir apropiadamente
  referencias cruzadas, sigue las indicaciones que verás al final del
  documento “manuscrito.Rmd”, sección “Nota sobre las referencias
  cruzadas” (más instrucciones en el aula, por vídeos o en el foro). Usa
  un sistema de referencia cruzada asistido por RStudio en tu RMarkdown
  (además de mis indicaciones y sugerencias, pregunta a tu tutor de
  inteligencia artificial de preferencia cómo, en RStudio, insertar
  títulos a tablas y figuras, y cómo referirlos en el texto; también
  pregúntale cómo insertar y referir fórmulas).

- **Resultados** (tamaño mínimo: 4 párrafos). Básicamente, deberás
  redactar qué obtuviste tras analizar tus datos. No hagas valoraciones
  en esta sección, simplemente incluye los resultados obtenidos. Este es
  el lugar para incluir los análisis que hayas realizado, pero sólo los
  relevantes; asimismo, incluye los resultados de pruebas estadísticas,
  gráficos y tablas (dos o tres tablas, y dos o tres gráficos, son
  normalmente suficientes). No desbordes esta sección con párrafos que
  enumeran de forma exhaustiva las tablas. Tampoco incluyas tablas
  gigantes ni gráficos ilegibles, sino básicamente los extractos más
  relevantes. Las tablas muy largas, deberían incluirse en una sección
  final de información suplementaria. Igualmente, si hay gráficos que
  pertenecen al estudio, pero no son centrales sino más bien de apoyo,
  también deberían incluirse sólo en la sección de información
  suplementaria.

- **Discusión** (tamaño mínimo: 4 párrafos). Abre la discusión indicando
  si alcanzaste tus objetivos. Describe por qué era importante
  alcanzarlos. Comenta sobre las limitaciones, de cualquier tipo, ya sea
  las limitaciones de los datos, de la técnicas, de los objetivos de
  aprendizaje. Cierra indicando qué desafíos futuros quedan abiertos
  tras este trabajo.

- **Referencias**. Las referencias que hayas citado en el texto, se
  incluirán automáticamente en la sección “Referencias”. No obstante,
  debes verificar la integridad de las mismas.

> **RECUADRO: recomendaciones básicas de redacción**
>
> Usa una voz (activa o pasiva) de forma consistente, pero sólo ten
> presente que la redacción de manuscritos científicos a menudo se
> utilizan ambas voces, dependiendo del contexto y el mensaje que el/la
> autor/a quiera transmitir. Veamos algunos ejemplos:
>
> **Voz activa en manuscrito científicos:**
>
> - **Analicé** los datos utilizando el lenguaje de programación R.
>
> - El experimento **mostró** que la temperatura afecta directamente la
>   tasa de reacción.
>
> - Los investigadores **encontraron** una correlación significativa
>   entre las dos variables.
>
> La voz activa puede hacer que la redacción parezca más directa y
> clara, y es especialmente útil cuando el/la autor/a quiere enfatizar
> quién llevó a cabo una acción o cuándo se desea hacer una afirmación
> fuerte.
>
> **Voz pasiva en artículos científicos:**
>
> - Los datos **fueron analizados** utilizando el software R.
>
> - **Se observó** que la temperatura afecta directamente la tasa de
>   reacción.
>
> - Una correlación significativa **fue encontrada** entre las dos
>   variables.
>
> La voz pasiva es común en la redacción científica porque a menudo se
> prefiere un tono más impersonal, enfocando la atención en los
> resultados y procedimientos en lugar de en quienes llevaron a cabo la
> investigación. También puede ser útil cuando no se quiere o no es
> relevante especificar quién realizó la acción.
>
> **En todas mis prácticas, está completamente permitido usar IA (más
> específicamente, LLM, e.g. chatGPT), pero te recomiendo que la uses
> más como tutor que como redactor**. Tal como te sugerí arriba, no le
> pidas que te resuelva los problemas del mandato. Pídele que te dé
> ideas, y que luego tú las mejores o las descartes. No abuses tampoco
> del texto, pues mucha redacción no siempre es mejor; en redacción de
> ensayos “menos es más”. Cruza las redacciones que te ofrezca con tu
> conocimiento, y revisa si los términos o conceptos usados son
> descabellados (toda IA se inventa cosas, cuidate de no caer en esa
> trampa). Nunca le pidas referencias bibliográficas, porque se va
> equivocar.

# Referencias
