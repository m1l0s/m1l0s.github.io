# m1l0s.io

Personal website — a quiet landing page, still under construction.

**Live:** [m1l0s.io](https://m1l0s.io)

## Pages

| File | Description |
|---|---|
| `index.html` | Hero page with animated birds, portrait, live countdown, and contact button |
| `about.html` | About page with passions (Radio, Apple, Espresso) |
| `style.css` | All styles — single shared stylesheet |
| `assets/me.png` | Portrait photo |

## Stack

Vanilla HTML + CSS. No build step, no dependencies.

## Deploy

Pushes to `main` automatically deploy to GitHub Pages via the workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml). Custom domain is set in [`CNAME`](CNAME).
