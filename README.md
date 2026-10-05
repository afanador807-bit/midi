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

La página `revisiones/index.html` reúne en una ruta formativa los temas de las tres clases del ABC de las revisiones sistemáticas: pregunta y protocolo, estrategia de búsqueda, selección de estudios, extracción, evaluación crítica, síntesis y reporte. Incluye enlaces a segmentos de los videos, una lista de decisiones con avance guardado en el navegador y fuentes metodológicas oficiales. El contenido distingue una guía de reporte (PRISMA), el alcance específico de PEDro y la decisión condicionada de realizar un metaanálisis.

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
