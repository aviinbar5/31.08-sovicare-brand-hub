# SoviCare Brand Hub

Static site. No build step — every file is plain HTML that opens in a browser.

## Deploy to GitHub Pages

1. Upload the entire contents of this folder to the root of `sovicare-brand-hub`.
2. Settings -> Pages -> Source: **Deploy from a branch**, Branch: `main`, Folder: `/ (root)`.
3. The site goes live at `https://<user>.github.io/sovicare-brand-hub/`.

## Contents

| File | Page |
|---|---|
| `index.html` | Hub — links to everything |
| `brand-book.html` | Full brand book |
| `styleguide.html` | One-scroll styleguide |
| `logo.html` | Logo construction and lockups |
| `brand-film.html` | Animated mood slides |
| `social-channels.html` | Profile and cover art |
| `screens-funnel.html` | Purchase funnel screens |
| `screens-portal.html` | Member portal screens |
| `screens-admin.html` | Clinical admin screens |
| `screens-support.html` | Support screens |
| `assets/people/` | Portrait photography |
| `support.js`, `download-chips.js`, `image-slot.js` | Runtime scripts |

All paths are relative, so the site works from any sub-path.
`.nojekyll` is present so GitHub Pages serves every file as-is.
