# Northwind ? Lumos for Astro

This project uses the official [Lumos for Astro](https://github.com/lumosframework/lumos-for-astro) component and styling framework. The existing home and about routes have been migrated to Lumos components.

Requires Node.js 22.12 or newer. Run npm install, then npm run dev.

## Commands

- npm run dev: start the development server.
- npm run check: type-check Astro and TypeScript.
- npm run build: generate the static site in dist/.
- npm run preview: preview the production build.
- npm run format: format source files.

## Project structure

- src/pages/: home, about, component examples, and 404 routes.
- src/components/: Lumos layout, content, media, form, and interactive components.
- src/layouts/BaseLayout.astro: shared page shell.
- src/styles/base.css: design tokens and themes.
- src/styles/patterns.css and utilities.css: shared styles.
- src/consts.ts: site identity and SEO settings.
- LUMOS.md: component and styling conventions.

Set SITE_URL to your production origin before deployment (see .env.example). Without it, local metadata uses localhost and sitemap generation is disabled. The GitHub repository connection does not publish the website.

The lumos entry in package.json records the upstream version and commit used for this migration. Framework license: LICENSE-LUMOS.
