# Front-End Chronicles – Bento mirror

Static Astro version of <https://bento.me/fec> ready for GitHub Pages.

## Setup

```bash
npm install
npm run dev
```

## Build

```bash
npm run build   # outputs to dist/
npm run preview # serve the static build locally
```

## Deploy on GitHub Pages

A workflow in `.github/workflows/deploy.yml` builds `dist/` on every push to `main` and deploys to the `github-pages` environment. Make sure Pages is enabled for the repo and that the default branch matches the workflow trigger.
