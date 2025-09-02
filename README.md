Un Toque de Deco — Sitio web de velas artesanales

Sitio estático para mostrar catálogo, galería y contacto de Un Toque de Deco.
Construido con HTML5, SCSS (Sass), AOS (Animate On Scroll) por CDN y tipografías de Google Fonts.

🔗 Demo

    GitHub Pages: agregar enlace cuando publiques

    Página inicial: index.html

📁 Estructura

    ├── index.html
    ├── pages/
    │   ├── velas.html
    │   ├── galeria.html
    │   └── sobreNosotros.html
    │   └── contacto.html
    ├── img/
    │   ├── logo.png
    │   ├── vela1.jpeg ... vela14.jpg
    │   └── hero.png
    ├── style.css         # Generado desde SCSS
    ├── style.scss        # con @use 
    └── scss/
        ├── base/
        │   ├── _variables.scss
        │   ├── _mixins.scss
        │   └── _globals.scss
        ├── layout/
        │   ├── _header.scss
        │   └── _footer.scss
        └── pages/
            ├── _hero.scss
            ├── _velas.scss
            ├── _galeria.scss
            ├── _sobre-nosotros.scss
            └── _contacto.scss

🧩 Tecnologías / Librerías

    HTML5 + CSS3

    Sass/SCSS (arquitectura por parciales con @use)

    AOS (CDN) para animaciones al hacer scroll

    Google Fonts: Poppins

    Prettier (formateo consistente)

🎨 Diseño

Paleta (pasteles rosados y crema):

    Rosa claro: #F8C9D4

    Rosa medio: #E2A9B8

    Crema base: #FFF8F0

    Beige contornos: #F5E1CE

    Marrón texto: #8C6A5D

    Tipografía: Poppins (300–600)

✨ AOS (Animate On Scroll)

CDN:

    <link rel="stylesheet" href="https://unpkg.com/aos@2.3.4/dist/aos.css" />
    <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
    <script>AOS.init();</script>


Uso básico (data attributes):

    <header data-aos="fade-down">...</header>
    <article data-aos="fade-up">...</article>
    <img data-aos="zoom-in" src="..." alt="..." />

✍️ Autor

    Un Toque de Deco
    Instagram: @untoqueddeco
