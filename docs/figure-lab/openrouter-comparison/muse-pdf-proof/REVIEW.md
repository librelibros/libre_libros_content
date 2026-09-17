# Muse: prueba de portada en PDF

Estado: prueba técnica; no aprobada para publicación ni integración.

> Nota de limpieza (2026-09-17): los artefactos binarios de esta prueba (PDF,
> renderizaciones y copia de la imagen) se retiraron del repositorio para no
> redistribuir material con derechos sin verificar; se conservan solo en el
> equipo local. Las conclusiones de esta página siguen siendo válidas.

## Alcance y comprobaciones

- PDF temporal de Matemáticas Infantil generado con el servicio real `app.services.pdf_export.render_pdf` y una copia del libro.
- Título compuesto mediante tipografía local, no generado por IA.
- Resultado: 4 páginas, 2 imágenes incrustadas; el loader cargó `assets/muse.png` y `assets/numeros-colores.png`.
- Hashes del libro original comparados antes/después: sin cambios.
- Renderizaciones de las cuatro páginas revisadas por un subagente de visión. Es revisión automatizada, no validación docente ni prueba de impresión física.

## Resultado visual comunicado por el revisor

La imagen Muse está completa; el título compuesto es legible y no invade la ilustración. No se reportan cortes del cuerpo de texto ni solapes con los pies de página.

Problemas pendientes del documento:

- Títulos redundantes: título del exportador, encabezado Markdown y título dentro de la imagen.
- Texto alternativo impreso como líneas `[Imagen: ...]`; decidir su presentación sin perder accesibilidad.
- Encabezado «Presentacion» huérfano al final de la primera página.
- Tildes ausentes en el contenido original.
- Mucho espacio vacío en páginas interiores; revisar junto con los saltos manuales y el uso didáctico previsto.
- La segunda imagen original presenta un círculo recortado a la derecha según el revisor; requiere evaluación independiente del recurso.
- Afinar el alt de la portada: «triángulos verde azulado» describe mejor el color que «verdes».

Estos hallazgos no se han corregido en los originales. La prueba no completa la revisión pendiente de las nueve portadas del catálogo.

## Derechos: bloqueo abierto

Consulta del 17 de septiembre de 2026:

- Los términos de OpenRouter remiten los derechos sobre los outputs a los Model Terms de cada modelo: https://openrouter.ai/terms
- La ficha https://openrouter.ai/meta/muse-image y los metadatos públicos https://openrouter.ai/api/v1/models/meta/muse-image/endpoints no proporcionaron en las respuestas consultadas unas condiciones suficientes para confirmar publicación, redistribución o compatibilidad con la licencia del proyecto.
- Las búsquedas complementarias no resolvieron la cuestión. No se infiere autorización de esa ausencia, del pago de la generación ni de información promocional.

Antes de publicar: obtener las condiciones oficiales aplicables a Muse vía OpenRouter/Meta, comprobar uso editorial y redistribución, obligaciones de atribución y compatibilidad con la licencia del proyecto. No se declara que su uso esté prohibido: los derechos permanecen sin verificar.

## Archivos

- Los binarios de la prueba (`matematicas-infantil-muse-prueba.pdf`,
  `cover-with-title.png`, `page-1.png`–`page-4.png`) se retiraron del
  repositorio el 2026-09-17: derechos de la imagen sin verificar y peso
  innecesario en Git. Permanecen solo en el equipo local.

No se han generado imágenes adicionales durante esta revisión ni se ha integrado o desplegado esta portada.
