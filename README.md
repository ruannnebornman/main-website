# Ruanne Bornman Personal Website

An Astro personal website with an illuminated-manuscript / fantasy Linux codex style. The site is a single long page for personal branding, Veldmuis Linux, work history, craft inventory, public GitHub work, and contact links.

## Stack

- Astro
- TypeScript
- Plain CSS
- Optimized local image assets

## Local Development

Install dependencies:

```sh
npm install
```

Run locally:

```sh
npm run dev
```

Because the site is configured as a GitHub Pages project site, the dev URL is:

```txt
http://127.0.0.1:4321/main-website/
```

## Checks

Run Astro diagnostics:

```sh
npm run check
```

Build the static site:

```sh
npm run build
```

Preview a production build:

```sh
npm run preview
```

## Project Layout

- `src/pages/index.astro` - page content and small inline browser behavior.
- `src/styles/global.css` - manuscript framing, responsive layout, typography, and ornament styling.
- `src/assets/ornaments/` - optimized decorative manuscript assets used by CSS.
- `src/assets/` - optimized image assets used by Astro.
- `.github/workflows/deploy.yml` - GitHub Actions workflow for GitHub Pages.

## Deployment

The site is configured for GitHub Pages at:

```txt
https://ruannnebornman.github.io/main-website/
```

Deployment runs automatically on pushes to `main` using GitHub Actions.

In GitHub repository settings, Pages should use **GitHub Actions** as the build and deployment source.

## Notes

- The ticker is shuffled on page load so the title list feels different each visit.
- The VAT IT duration is calculated from the start month and updates in the browser.
- `docs/`, `refs/`, `dist/`, `.astro/`, and `node_modules/` are ignored and not part of the deployed site source.
