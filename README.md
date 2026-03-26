# Portfolio Profesional — Yashub Armando Guzmán Espinoza

Sitio web de portfolio profesional enfocado en **empleabilidad** (reclutadores) y presentación clara de experiencia en **sistemas web, backend y arquitectura**.

## Demo

- **Demo (producción)**: `https://yashub.com`

## Características

- **Diseño moderno tipo SaaS**: minimalista, profesional y orientado a lectura rápida.
- **Totalmente responsive**: desktop / tablet / mobile, con navegación móvil.
- **Modo oscuro**: persistente (usa `localStorage`).
- **Animaciones suaves**: reveal al hacer scroll + micro-interacciones.
- **Recursos locales**: fuentes y Tailwind incluidos en `assets/` (sin depender de CDNs para su consumo).
- **Accesibilidad básica**: “skip to content”, labels/aria en botones.
- **UX para reclutadores**: CTA claros, secciones bien separadas y contenido directo.

## Stack

- **HTML5**
- **CSS3**
- **JavaScript (vanilla)**
- **TailwindCSS** (incluido localmente)

## Estructura del proyecto

```text
.
├─ index.html
└─ assets/
   ├─ tailwind-cdn.js
   ├─ fonts.css
   └─ fonts/
      └─ *.ttf
```

## Nota

Este es un **proyecto estático**.

Si te gusta el diseño, **puedes tomarlo sin problema y adaptarlo a tus necesidades** (cambia textos, enlaces y secciones).

## Personalización rápida

Edita `index.html` para:

- **Nombre, rol y tagline**: sección Hero.
- **Proyecto destacado (SIISU)**: características/rol/impacto.
- **Enlaces**:
  - Email: `mailto:...`
  - GitHub: `https://github.com/...`
  - LinkedIn: `https://www.linkedin.com/in/...`
- **Años de experiencia (dinámico)**:
  - Fecha de inicio configurada en JavaScript (actualmente: `1 de noviembre de 2021`).

## Buenas prácticas / Notas

- Este repositorio es público: evita subir archivos sensibles (tokens, llaves, `.env`, credenciales).
- Si cambias rutas de `assets/`, actualiza los `href/src` correspondientes en `index.html`.

## Licencia

Este proyecto está bajo licencia **MIT**.

Puedes usar, copiar, modificar y distribuir el código libremente, conservando el aviso de licencia y copyright.

