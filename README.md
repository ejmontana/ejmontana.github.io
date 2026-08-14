# ejmontana.github.io

Portafolio profesional de [Enderson Montaña](https://ejmontana.github.io) — Full Stack Developer & Tech Lead.

## Stack

- [Astro 5](https://astro.build) — sitio estático, cero JS innecesario
- [Tailwind CSS 4](https://tailwindcss.com) — sistema de diseño con tokens propios
- Tipografías autoalojadas (Inter Variable + JetBrains Mono) — sin requests externos
- Deploy automático a GitHub Pages con GitHub Actions en cada push a `main`

## Desarrollo

```bash
npm install
npm run dev      # servidor de desarrollo
npm run build    # build de producción en dist/
npm run preview  # previsualizar el build
```

## Estructura

```
src/
  components/   Secciones de la página (Hero, IA, AWS, Experiencia...)
  layouts/      Layout base con SEO y reveal-on-scroll
  pages/        index.astro
  styles/       global.css — tokens de diseño y componentes
public/
  cv/           CV descargable
.github/
  workflows/    Deploy a GitHub Pages
```
