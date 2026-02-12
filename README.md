# haiyangzhang.org (Quarto)

This repository contains the Quarto version of https://haiyangzhang.com.

## Current structure

- `/` Home (`index.qmd`)
- `/research/` (`research/index.qmd`)
- `/teaching/` (`teaching/index.qmd`)
- `/contact/` (`contact/index.qmd`)
- `/flying/` (`flying/index.qmd`)

## Local development

1. Install Quarto CLI: https://quarto.org/docs/get-started/
2. Preview locally:

```bash
quarto preview
```

## Build

```bash
quarto render
```

Generated site output goes to `_site/`.

## Migration checklist

1. Export WordPress content and media.
2. Copy page content into corresponding `.qmd` files.
3. Move images into `assets/images/` and update links.
4. Keep URL slugs stable to preserve SEO.
5. Add redirects for any changed URLs.
6. Verify metadata, sitemap, analytics, and robots rules.
7. Switch DNS only after parity checks.

## Deploy options

- GitHub Pages (workflow included)
- Netlify
- Vercel
