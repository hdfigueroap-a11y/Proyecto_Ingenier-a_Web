# Portafolio personal — Hector Figueroa

Sitio de una sola página construido con HTML5 semántico y CSS Flexbox, como evaluación práctica individual del Módulo 1 (Actividad 4).

**Demo en vivo:** https://proyecto-ingenier-a-web.vercel.app/

## Descripción

Portafolio profesional para mostrar perfil, proyectos y habilidades a reclutadores, con formulario de contacto. Diseñado con una identidad visual propia ("ledger + terminal") que combina tipografía serif para títulos, monospace para etiquetas, y una paleta navy/mustard/teal sobre papel cálido.

## Estructura del contenido

- **Sobre mí** — foto, presentación y una cita destacada en `<aside>`.
- **Proyectos** — galería de tarjetas (`<article>`) con Nexus Eco, SalonFlow ERP, Sistema de biblioteca y Bitácora de entrenamiento.
- **Habilidades** — lista de chips con el stack técnico (Python, SQL, JavaScript, Node.js, React, PostgreSQL, Java, Git, Unity, Blender).
- **Contacto** — formulario con nombre, correo y mensaje.

## Requisitos técnicos cumplidos

- HTML5 semántico: `<header>+<nav>`, `<main>` con `<section>` por bloque, `<article>` por proyecto, `<aside>`, `<footer>` con `<nav>` de redes sociales.
- Layout Flexbox mixto: la sección "Sobre mí" usa `flex-direction: row` y cambia a `column` en pantallas pequeñas (media query en 700px).
- `align-self` aplicado al bloque de la cita para diferenciarlo del resto de los ítems.
- Galería de proyectos con `flex-wrap: wrap` y `flex-basis`/`min-width` para evitar desbordes.
- Chips de habilidades distribuidos con `flex-wrap` y espaciado uniforme (`gap`).
- Formulario maquetado como columna flex con `gap` entre campos, y `<label for>` asociado a cada input.

## Archivos

- `index.html` — estructura semántica de la página.
- `styles.css` — estilos y layout Flexbox.
- `captura-desktop-1280px.png` / `captura-mobile-375px.png` — capturas de pantalla en dos tamaños de viewport.

## Stack

HTML5, CSS3 (Flexbox), sin frameworks ni dependencias de JavaScript. Desplegado en Vercel.
