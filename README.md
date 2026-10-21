# Portafolio

Sitio web de portafolio personal de una desarrolladora Full-Stack Junior, creado como proyecto del Sprint 4 de TripleTen. La página presenta un perfil profesional, las habilidades y herramientas, una selección de proyectos destacados y los datos de contacto.

**Ver el sitio en GitHub Pages:** [https://alejandro160893.github.io/web_project_portfolio_es/](https://alejandro160893.github.io/web_project_portfolio_es/)

## Tecnologías

- HTML5 semántico
- CSS3 (sin frameworks ni JavaScript)
- Figma (diseño de referencia en 1440px, 768px y 320px)
- Git y GitHub Pages

## Técnicas utilizadas

- **Metodología BEM** para nombrar las clases.
- **Flexbox y Grid** para la maquetación; `position: absolute` solo en el velo y los iconos de las tarjetas de proyectos.
- **Diseño responsivo** con dos puntos de quiebre: `max-width: 1023px` (tablet) y `max-width: 767px` (móvil). Cada media query contiene solo las propiedades que cambian.
- **Variables CSS** para colores, fuentes, márgenes de página y la posición del brillo de fondo (`--accent: #6d6dff`).
- **Fuentes locales** (Inter en 400, 500 y 700 para el texto, y Noto Serif cursiva en 400 para los títulos) cargadas con `@font-face` en formatos `.woff2` y `.woff`, con fuentes del sistema de respaldo.
- **Fondo brillante** hecho con degradados radiales y `calc()`, sin imágenes.
- **Subrayado degradado** en los enlaces del perfil mediante `background-image`.
- **Velo degradado** sobre las imágenes de los proyectos con un elemento `.card__overlay` posicionado de forma absoluta.
- **Estados `:hover` y `:focus-visible`** en todos los enlaces.
- **Iconos SVG** exportados del diseño de Figma.

## Estructura

```
├── index.html
├── images/     Fotografías e iconos SVG
├── styles/     index.css
└── vendor/     normalize.css, fonts.css y fonts/ (Inter y Noto Serif, .woff2 / .woff)
```
