# Portfolio - Javier Garrido Terrón

Portfolio personal de un desarrollador full stack autodidacta. Single-page built con Astro, desplegado en GitHub Pages.

## Stack

- **Astro** — framework estático
- **HTML / CSS** — sin frameworks CSS, todo custom
- **JavaScript** — animaciones, canvas, efectos interactivos

## Estructura

```
/
├── public/
│   ├── certificates/     # Certificados en PDF
│   ├── favicon.svg
│   └── og-image.svg      # OG image para redes sociales
├── src/
│   ├── components/       # Componentes Astro
│   │   ├── Hero.astro       — Partículas canvas, gradient mesh, typing effect
│   │   ├── Nav.astro        — Glassmorphic, scroll progress, mobile drawer
│   │   ├── About.astro      — Avatar orbital, stat counters, tech mini-cards
│   │   ├── Skills.astro     — Clean badges con barras de progreso
│   │   ├── Projects.astro   — Cards con 3D tilt, filtros por tech
│   │   ├── Timeline.astro   — Glow line, chips
│   │   ├── Certificates.astro — Modal PDF con backdrop blur
│   │   ├── Contact.astro    — Cards con hover magnético
│   │   └── Footer.astro     — Logo, nav, social links
│   ├── layouts/
│   │   └── Layout.astro     — Global styles, CSS variables, meta tags
│   └── pages/
│       └── index.astro      — Ensambla todos los componentes
├── astro.config.mjs
└── package.json
```

## Desarrollo

```bash
npm install
npm run dev        # localhost:4321
npm run build      # build en ./dist/
npm run preview    # preview del build
```

## Despliegue

GitHub Pages: [https://javigt97.github.io/portfolio](https://javigt97.github.io/portfolio)
