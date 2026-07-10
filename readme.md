# HTML - CSS

- Lenguaje HTML y hojas de estilo CSS AF 33109 - Grupo 98418
- Duración: 24 horas
- Fecha inicio: 06/07/2026
- Fecha fin: 10/07/2026
- Horario: 9:00 - 14:00 de lunes a jueves / 9:00 - 13:00 viernes

- Instructor: Alejandro Cerezo Lasne <alce65@hotmail.es>
- Repositorio: <https://github.com/IconoTC/Lenguaje-HTML-y-hojas-de-estilo-CSS-AF-33109---Grupo-98418>

## Temario original

- Arquitectura de aplicaciones Web. 
- Herramientas para la construcción de páginas HTML. 
- El lenguaje HTML. 
- Estructura básica de un documento HTML. 
- Organización de texto. 
- Hipertexto. 
- Imágenes. 
- Tablas. 
- Frames. 
- Hojas de estilo, reglas y propiedades. 
- La entrada de usuario. Formularios. 
- Objetos multimedia


<!-- 

Contenido del curso HTML5 Y CSS3 AF 75948 (25h)

- HTML. 
    - Arquitectura de aplicaciones Web. 
    - El lenguaje HTML. 
    - Estructura básica de un documento HTML. 
    - Organización de texto. 
    - Hipertexto: links HTML. 
    - Imágenes. 
    - Tablas. 
    - La entrada de usuario. Formularios. 
    - Interacción con CSS. 
    - Interacción con JavaScript. 
- HTML5. 
    - Compatibilidad de los navegadores. 
    - Artículos, secciones, cabeceras. 
    - Nuevos componentes de formulario. 
    - Audio. 
    - Video. 
    - Otras APIs de intercambio de información. 
- CSS3. 
    - Arquitectura, propósito y alcance de CSS. 
    - Inclusión de elementos CSS en páginas HTML5. 
    - Hojas de estilo, reglas y propiedades. 
    - Herencia de estilos: resolución de conflictos. 
    - Tratamiento de textos. 
    - Gestión de imágenes. 
    - Organización de tablas. 
    - Definición de la estructura de una página HTML5. 
    - Transformaciones, transiciones y animaciones. -->

## Desarrollo

### Dia 1 (Lunes 01/06/2026)

- Presentación formador y alumnos. Curso
- Requisitos técnicos
  - Navegador web actualizado (Google Chrome, ...)
  - Editor de código (Visual Studio Code, ...)
  - Repositorio GitHub
    - Documentación
    - Recursos y tools
- Introducción a HTML
  - Arquitectura de aplicaciones Web
  - El lenguaje HTML (demo-01)
    - Etiquetas y atributos
    - Hipertexto: links HTML
    - Imágenes
    - Comentarios 

- Validación y estructura de un documento HTML (demo-02)
  - Elementos imprescindibles y recomendables
  - Documentos HTML5_ html, head, body

[descanso] 11:25 - 11:55

- HTML en la Web (demo-03)
  - Etiquetas más usadas: p, h1-h6, a, img, div, ul, li
  - Interacción con CSS
  - Interacción con JavaScript

- Elementos del head (demo-04)
  - Metadatos
  - Título de la página
  - Enlaces a recursos externos: favicon, CSS, JavaScript, fuentes, ... 
  - Metadatos para SEO y redes sociales

- Revisión del estándar HTML. Clasificación de etiquetas.  

- Etiquetas principales de HTML (demo-05): Porfolio


### Dia 2 (Martes 02/06/2026)

- Etiquetas principales de HTML (demo-05): Porfolio
  
- Semántica en HTML5 y roles Aria
- Sectioning:
    - `<header>`: Encabezado de una sección o página.
    - `<footer>`: Pie de página o sección.
    - `<main>`: Contenido principal de la página (etiqueta de grouping).
    - headings: `<h1>` a `<h6>`: Títulos y subtítulos de secciones.
    - `<hgroup>`: Agrupación de encabezados y párrafos relacionados.
    - `<nav>`: Contenedor de enlaces de navegación.
    - `<section>`: Agrupación temática de contenido.
    - `<article>`: Contenido independiente y autocontenible.
    - `<address>`: Información de contacto del autor o propietario de la página.
    - `<aside>`: Contenido relacionado pero separado del contenido principal.

- roles aria y aria-label
- header y footer en secciones y artículos
- uso de clases y css para cambiar la estética de los elementos semánticos (e.g. headings)
- validación de la estructura

Otras etiquetas:
  - grouping
    - párrafos: `<p>`
    - listas: `<ul>`, `<ol>`, `<li>`, `<menu>` 
  - `<dl>`, `<dt>` and `<dd>`

[descanso] 11:30 - 12:00

- Otras etiquetas de sectioning y grouping
  - `<div>`: Contenedor genérico sin significado semántico específico (etiqueta de grouping).
  - `<hr>` 
  - `<pre>` 
  - `<blockquote>`

- enlaces (anchor): `<a>`: enlaces externos o internos a la página 
- Nueva página 'contactos': enlaces entre páginas

- Text formatting:
  - `<strong>`: Texto importante.
  - `<em>`: Texto enfatizado.
  - `<small>`: Texto de menor importancia.
  -` <span>`: Contenedor en línea sin significado semántico específico.
  - ...

- Embedding content:
  - `<img>`: Incrustación de imágenes en la página.
  - `<figure>` and `<figcaption>` 
  - `<iframe>`: Incrustación de otra página web dentro de la actual.
  - `<iframe>`: Videos de YouTube.
  - `<video>`: Reproducción de video.
  - `<audio>`: Reproducción de audio.

### Dia 3 (Miércoles 03/06/2026)

- Formularios:
  - `<form>`: Contenedor para elementos de formulario.
  - `<input>`: Campos de entrada de datos.
  - `<textarea>`: Área de texto multi-linear.
  - `<select>`: Menú desplegable.
  - `<button>`: Botón interactivo.
  - `<label>`: Etiqueta para elementos de formulario.

- Tablas en html
  - `<table>`: Contenedor para una tabla de datos.
  - `<tr>`: Fila de la tabla.
  - `<th>`: Celda de encabezado de la tabla.
  - `<td>`: Celda de datos de la tabla.

- Elementos interactivos
  - De otros tipos: `<a>`, `<button>` (diferencias), `<input>` ...     
  - `<details>`: Contenido adicional que el usuario puede mostrar u ocultar.
    - `<summary>`: Resumen o título para el contenido de `<details>`.
  - `<dialog>`: Diálogo modal o ventana emergente.
  - JS: in-line v. scripts internos o externos
  - atributo `popover`

[descanso] 11:10 - 11:40

- CSS
  - Concepto de CSS: propósito,
  - Inclusión de CSS en HTML: inline, interno, externo 
  - Arquitectura de CSS: selectores, propiedades, valores, reglas, hojas de estilo 

- Selectores CSS
  - Selectores básicos: por etiqueta, clase, id
  - Selectores de agrupación y descendencia
  - Alternativa actual: anidamiento (nesting) de selectores
  - Selectores de atributos
  - Pseudo-clases y pseudo-elementos

- Especificidad y herencia de estilos
  - Reglas de especificidad: inline > id > clase > etiqueta

### Dia 4 (Jueves 04/06/2026)


- Especificidad y herencia de estilos (2)
  - Reglas de especificidad: inline > id > clase > etiqueta
  - Herencia de estilos: cómo los estilos se propagan a través del árbol DOM
  - Resolución de conflictos: cómo se aplican los estilos cuando hay múltiples reglas que coinciden  


- Elementos del lenguaje CSS
  - Pseudo-elementos: 
    - `::first-letter`, 
    - `::first-line`,
    - `::before`, 
    - `::after`,
    - `::marker`,
  - Pseudo-clases: 
    - `:target`,
    - `:hover`, 
    - `:focus-visible`, 
    - `:nth-child()`, ...

  - Variables y funciones CSS
    - Variables CSS: `--nombre-variable`
    - Funciones CSS: `calc()`, `var()`, `rgb()`, ...
    - Paletas de colores
    - Escala de tamaños para la tipografía

[descanso] 11:30 - 12:00

    - Guías de estilo (Style Guides)
    - Hojas de CSS básicas

- Elementos del lenguaje CSS (continuación)
  - Unidades de medida en CSS
    - Absolutas: `cm`, `mm`, `in`, `pt`, `pc`
    - Absolutas (por dispositivo): `px` 
    - Relativas: `%`, `em`, `rem`, `vw`, `vh`, `vmin`, `vmax`
    - Rem vs Em

- Diseño (Layout) de páginas web con CSS

  - Box model: contenido, padding, border, margin
    - Box-sizing: content-box vs border-box
  - Display: block, inline, inline-block, none
  - Layouts clásicos: float, clear, inline-block
  - Flexbox: diseño flexible
    - contenedores

### Dia 5 (Viernes 05/06/2026)

- Diseño (Layout) de páginas web con CSS
  - Flexbox (continuación): diseño flexible para contenedores y 
    - elementos hijos
  - Grid: diseño de cuadrícula para organizar elementos en filas y columnas 

[descanso] 11:00 - 11:30

- Encuesta: <https://forms.cloud.microsoft/pages/responsepage.aspx?id=tA7tEz6_F0GYpeEuIOyC74dmltakDyZNkCB0fAWABS1URDVXNlRLSzZRRDI3VjNVSFJISkoyRkRITSQlQCN0PWcu&route=shorturl>


- Position: static, relative, absolute, fixed & anchors
- Columns (propiedad de CSS)

- Responsive Web Design (RWD)
  
  - Media queries: diseño adaptativo para diferentes tamaños de pantalla
  - Enfoques de diseño:
    - Mobile-first
    - Desktop-first
    - Mobile-only
  - Mobile-first design: enfoque de diseño que prioriza la experiencia móvil
    - Cambios de display (e.g. Menus hamburguesa)

  - CSS Dinámico
    - Transformaciones, transiciones y animaciones