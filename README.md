# MediCloud 1.0.0

MediCloud — a modern one-page landing template for telehealth / digital-health SaaS products. Built with **Vite**, **Bootstrap 5**, **Sass**, **GSAP** animations and **Tabler Icons**. Ships with hero, features, about, doctor/team, pricing, testimonials, FAQ and CTA sections — all client-side and responsive.

## Features

- One-page telehealth SaaS landing template (hero, features, stats, about, doctors, pricing, testimonials, FAQ, footer)
- Bootstrap 5 grid + utility styling with a custom Sass theme layer
- GSAP scroll-based animations and interactive UI touches
- Tabler Icons webfont icon set, SVG client logos, avatar imagery
- Fully static output — no backend, no login, no build-time secrets
- Fast Vite 6 build pipeline with cache-busted hashed assets

## Tech Stack

- **Vite 6** — build tooling / dev server
- **Bootstrap 5.3** + **Sass** — layout and styling
- **GSAP 3** — scroll animations
- **Tabler Icons** — icon set
- Plain JavaScript (no framework)

## Quick Start

```bash
cd medicloud-1.0.0
npm install
npm run dev      # local dev server with hot reload
npm run build    # production build -> dist/
npm run preview  # preview the production build
```

## Project Structure

```
medicloud-1.0.0/
├── src/
│   ├── index.html        # landing page template
│   ├── assets/           # images, logos, avatars, favicons
│   └── js/               # entry scripts, GSAP animation wiring
├── vite.config.js
└── package.json
```

## Deploy Notes

Static build: `npm run build` outputs to `dist/` — host anywhere static files are served (Cloudflare Pages, Netlify, GitHub Pages). No environment variables required.

## License

Template derived from the ThemeWagon MediCloud theme; see `package.json` and upstream for license terms.

---

Built by [Girish Lade](https://github.com/girishlade111) · [ladestack.in](https://ladestack.in)
