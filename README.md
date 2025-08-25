---
title: "Readme"
format:
  html:
    css: styles.css
---

# Your Bio Site

A multi-page personal site in Markdown (with tiny HTML for nav/styles).

## Pages
- `index.md` — Home
- `about.md` — About Me
- `portfolio.md` — Portfolio
- `resume.md` — One-page Résumé
- `contact.md` — Contact
- `styles.css` — Global styles
- `assets/` — Images (placeholders included)

## Publish (GitHub Pages)
1) Push to a repo
2) Settings → Pages → Deploy from branch (main)
3) Ensure raw HTML is allowed (GitHub does).

## Customize
- Colors: edit CSS `:root` vars `--accent`, `--accent-2`
- Fonts: update the Google Fonts `@import`
- Light mode: toggle `body` class `light`
- Replace placeholders in `/assets` with your own images.