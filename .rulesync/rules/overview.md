---
root: true
targets: ["*"]
description: "Project overview and general development guidelines"
globs: ["**/*"]
---

# Project Overview

Merchandice is a Jekyll static site intended for GitHub Pages. The site is served from the repo root and uses the `minima` theme with content written in Markdown.

## Stack
- Jekyll (GitHub Pages)
- Theme: `minima`
- Markdown: `kramdown`
- Plugin: `jekyll-sitemap`
- Domain: `https://merchandice.in`

## Key Structure
- Root-level pages (e.g. `index.md`, `contact.md`, `privacy-policy.md`, `terms-of-use.md`).
- Layouts in `_layouts/`.
- Static assets in `assets/`.
- Site configuration in `_config.yml`.
- Custom domain config in `CNAME`.

## Development Notes
- Content changes are generally made in the root `.md` files.
- Avoid introducing non-ASCII characters unless the file already uses them.
- Keep pages compatible with GitHub Pages (no unsupported plugins).
