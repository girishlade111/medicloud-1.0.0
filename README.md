# MediCloud — Telehealth SaaS Landing Template

A polished one-page landing-page template for a telehealth SaaS product, built with **Vite**, **Bootstrap 5**, **Sass**, **GSAP** animations and **Tabler Icons**. Includes hero, features, doctor profiles, testimonials, pricing, FAQ and CTA sections — ready to adapt into any health-tech product site.

> The template source lives in the `medicloud-1.0.0/` folder. Theme design lineage: ThemeWagon / CodesCandy "MediCloud".

## Features

- One-page marketing site for a telehealth SaaS product
- Responsive Bootstrap 5 layout with custom Sass styling
- GSAP-powered scroll animations and counters
- Doctor profile cards, patient testimonials, pricing tables, FAQ accordion
- Tabler Icons webfont set + custom SVG assets
- Multi-page Vite build (all HTML pages under `src/`)
- Asset pipeline with organized `assets/css`, `assets/js`, `assets/images` output

## Tech Stack

- **Build:** Vite 6
- **UI:** Bootstrap 5.3, Sass, Popper.js
- **Animation:** GSAP 3.15
- **Icons:** Tabler Icons (JS + webfont)

## Quick Start

```bash
cd medicloud-1.0.0
npm install
npm run dev        # Vite dev server on :3000
npm run build      # production build -> medicloud-1.0.0/dist/
npm run preview    # preview the production build
```

## Project Structure

```
medicloud-1.0.0/
  vite.config.js     # Vite config (base './', root=src, multi-page)
  package.json
  src/
    index.html       # landing page entry (+ other pages)
    assets/
      images/        # logos, avatars, illustrations, favicon pack
      js/            # theme scripts
      scss/          # custom styles over Bootstrap
```

## Deploy Notes

- Static build: the `dist/` output is fully static (no server code). It is deployed to Cloudflare Pages (see repo homepage); any static host (GitHub Pages, Netlify) works.
- `base: './'` in `vite.config.js` makes asset paths relative, so it works under any sub-path.

## License

ISC. Original theme terms: ThemeWagon / CodesCandy.

---

Built by **Girish Lade** — https://ladestack.in
