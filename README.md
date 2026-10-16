# Página personal de Diego Fernando Afanador Restrepo

Sitio estático preparado para GitHub Pages. No requiere instalar dependencias ni ejecutar una compilación.

## Archivos

- `index.html`: página, estilos y catálogo interactivo.
- `favicon.svg`: icono personal.
- `.nojekyll`: sirve los archivos directamente.
- `assets/mascota-totodile.png`: mascota mostrada junto a los datos de contacto.

## Publicación

1. Crea o abre el repositorio de GitHub donde publicarás la página.
2. Sube estos archivos a la raíz del repositorio, conservando `index.html` con ese nombre.
3. En Settings → Pages, selecciona Deploy from a branch.
4. Elige la rama que contiene los archivos y la carpeta `/ (root)`; guarda la configuración.
5. GitHub mostrará el enlace cuando finalice la publicación.

## Brújula de investigación en salud

El catálogo enlaza a la herramienta interactiva `brujula/index.html`. Presenta un recorrido de decisiones para estudios cualitativos, cuantitativos y revisiones. Cada recorrido completo entrega una metodología concreta, una explicación y puntos que conviene revisar con el equipo docente. Incluye una guía de PICO, PEO/PECO, PICo, SPIDER, PCC, SPICE y PerSPEcTiF. La guía académica y el árbol completo acompañan la herramienta en `brujula/contenido-y-arbol-de-decisiones.md`.

## Incorporar herramientas y recursos

Edita la lista `TOOLS` al final de `index.html`. Cada herramienta tiene nombre, descripción, estado, público, color y URL. Si todavía no está publicada, conserva la URL vacía. La página mostrará el estado sin crear un enlace falso.

Edita `REPO` para incorporar guías y materiales por categoría. El buscador y los filtros actúan sobre las herramientas; los recursos se muestran agrupados.

GitHub Pages sirve archivos: incorporar una herramienta significa subir su aplicación estática o enlazar su ubicación. La página no incluye un formulario de carga de archivos ni un panel de administración.

## Contenido que debes revisar antes de publicar

Se conservaron de tu plantilla los datos de contacto, enlaces, líneas de investigación, proyectos y curso de diciembre de 2026. Verifica que sigan vigentes. Los perfiles académicos sin URL aparecen como pendientes.

El footer identifica la iniciativa como personal y conserva las licencias de los recursos externos; puedes definir una licencia propia para tus materiales y el código.

## Ruta de revisiones sistemáticas

La página `revisiones/index.html` organiza el contenido entregado en 13 etapas, desde la pregunta hasta el envío a revista. Los cinco apartados de cada etapa son agrupadores temáticos, no pasos uniformes; la secuencia la marca el menú lateral. El bloque ACHIEVE añade una anatomía visual adaptada a la etapa: fragmentos del artículo, diagramas PRISMA, tabla de características, evaluación PEDro, forest plots y gráfico de embudo, con preguntas de lectura crítica. Las figuras y fragmentos se presentan con atribución al artículo y licencia CC BY 4.0. También se señala una discrepancia entre el resumen y el cuerpo del artículo sobre el número de estudios incluidos en el metaanálisis para que el estudiante la verifique. El avance del checklist se guarda localmente. Las notas marcadas como pendientes se conservan visibles y las notas privadas para el docente se excluyeron. Las tres clases del ABC permanecen como videos complementarios. La guía se centra en revisiones de intervenciones en salud y deriva a Brújula cuando la pregunta pertenece a otro tipo de revisión.

## Escritura Científica

La herramienta `escritura-cientifica/index.html` articula la anatomía visual del artículo con el recetario de escritura entregado por el autor. Incluye la estructura del manuscrito, lenguaje y citación, recetas para organizar la introducción, la metodología, los resultados y la discusión, ejemplos de artículos publicados y filtros por diseño. Sus mesas de trabajo para introducción, resultados y discusión permiten redactar notas, ver un esquema de párrafos, cargar ejemplos y copiar el esquema; los borradores se guardan localmente en el navegador y no se sincronizan entre dispositivos. La navegación superior permite saltar entre las secciones y regresar a la página personal.

## Biblioteca de publicaciones

La página `publicaciones/index.html` organiza los registros de publicaciones extraídos del archivo de datos de FisioTIPS. Incluye 51 registros (47 artículos, 3 libros y 1 capítulo), búsqueda, filtros por tipo y estado, y enlaces DOI o URL cuando el registro los incluye. Dos libros están marcados “En proceso editorial”, tal como aparecen en los datos de origen.

## Ruta de Dosificación FITT-PV

La aplicación estática e interactiva se encuentra en `dosificacion/index.html` y se enlaza desde el catálogo de herramientas. No requiere un servidor ni archivos auxiliares. Mantiene visible su alcance: apoyo al razonamiento profesional, no sustitución del juicio clínico, y dosis operativas pendientes de validación clínica externa.

## Publicar recomendaciones

La portada muestra el contenido de `recomendaciones.json`. El formulario de `recomendaciones/admin.html` puede agregar entradas sin editar el HTML: ingresa el repositorio GitHub, la rama, la carpeta desde la que Pages sirve el sitio y un token fine-grained con permiso `Contents: Read and write` limitado a ese repositorio. El primer envío crea el archivo de datos; cada envío posterior agrega una recomendación y genera un commit. GitHub Pages sirve el nuevo contenido al completar su despliegue.

La contraseña del formulario es un filtro de interfaz en un sitio estático, no autenticación segura del servidor. La escritura real queda protegida por el token de GitHub: ingrésalo solo en una página confiable, no lo compartas ni lo guardes en el código. El token se solicita al publicar; si el repositorio no coincide con el directorio servido por Pages, el archivo no aparecerá en la portada.

## Referencia visual

Adaptación de la estructura HTML entregada por el usuario y del Manual de Identidad Visual Unicauca V2024: Open Sans (p. 13), azul RGB 0/18/130 y rojo RGB 173/0/0 (p. 14), colores complementarios (p. 15), placas y tótems de señalética (p. 39). No se reprodujo ni redibujó el escudo. La página se identifica como personal.

Open Sans se solicita a Google Fonts. Si no hay conexión, el sitio utiliza fuentes de sistema.
