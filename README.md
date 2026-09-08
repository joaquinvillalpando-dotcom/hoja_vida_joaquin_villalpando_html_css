# Hoja de Vida — Joaquin Francisco Villalpando Apaza

Hoja de vida personal desarrollada como página web estática, utilizando **HTML5 semántico** para la estructura y **CSS3 puro** para el diseño visual. Proyecto realizado para la asignatura **Tecnologías Web I** (Universidad Católica Boliviana "San Pablo").

**Ver la página en vivo:** https://joaquinvillalpando-dotcom.github.io/hoja_vida_joaquin_villalpando_html_css/
*(el enlace funciona una vez que actives GitHub Pages en Settings → Pages)*

---

## Sobre el proyecto

El sitio presenta mi perfil profesional como estudiante de Ingeniería de Sistemas: formación académica, experiencia práctica, habilidades técnicas, certificaciones, idiomas, proyectos destacados, portafolio multimedia y un formulario de contacto.

Todo el contenido se construyó sin frameworks ni librerías (sin Bootstrap, sin Tailwind, sin JavaScript), como restricción explícita del trabajo práctico.

## Estructura del proyecto

```
hoja_vida_joaquin_villalpando_html_css/
├── index.html
├── css/
│   ├── styles.css        # archivo maestro: importa el resto vía @import
│   ├── variables.css      # tokens de color, tipografía y espaciado
│   ├── base.css           # reset y tipografía base
│   ├── layout.css         # estructura general (Flexbox y CSS Grid)
│   ├── components.css     # tarjetas, formularios, tablas, botones
│   └── animations.css     # micro-interacciones sin JavaScript
├── assets/
│   ├── images/            # foto de perfil y poster del video
│   ├── audio/              # presentación en audio
│   ├── video/               # demostración audiovisual
│   └── documents/            # CV descargable en PDF
└── README.md
```

## Tecnologías utilizadas

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `details`, `dialog`, `figure`)
- CSS3 (Flexbox, CSS Grid, `@media` queries, `@keyframes`, custom properties)
- Sin JavaScript, sin frameworks ni librerías externas

## Características técnicas destacadas

- **Responsive:** breakpoints en 780px y 560px, con la cuadrícula de habilidades reorganizándose de 3 columnas a 1 en pantallas pequeñas.
- **CSS Grid:** usado en la sección de Habilidades (tres columnas: lenguajes, herramientas y habilidades profesionales) y en la lista de fortalezas del perfil.
- **Flexbox:** usado en el encabezado, la barra de navegación, la sección de multimedia, el formulario de contacto y las tarjetas del aside.
- **Interactividad sin JavaScript:** resaltado de sección al navegar por ancla (`:target`), acordeones nativos (`details`/`summary`) para formación y experiencia, y transiciones en hover/focus.
- **Accesibilidad:** enlace de salto al contenido principal, texto alternativo en imágenes, `label` asociado a cada campo del formulario, estados de foco visibles y soporte para `prefers-reduced-motion`.
- **Validación HTML5:** campos requeridos, patrones de validación y tipos de input apropiados (`email`, `tel`) en el formulario de contacto.

## Cómo verlo localmente

No requiere instalación ni dependencias. Basta con:

1. Clonar o descargar este repositorio.
2. Abrir `index.html` directamente en el navegador.

## Autor

**Joaquin Francisco Villalpando Apaza**
Estudiante de Ingeniería de Sistemas — Universidad Católica Boliviana "San Pablo"
La Paz, Bolivia
[joaquin.villalpando@ucb.edu.bo](mailto:joaquin.villalpando@ucb.edu.bo)

---

*Proyecto académico entregado en el marco del trabajo práctico "Hoja de Vida Personal con HTML5 + CSS3", con fecha de cierre el 7 de septiembre de 2026.*