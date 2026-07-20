# Garvin Inspired Charity Foundation — Website

A single-page, responsive website for Garvin Inspired Charity Foundation, built with plain HTML/CSS/JS (no build step required).

## Structure

```
.
├── index.html          # The full site
├── images/              # Photos and logo used on the site
│   ├── logo.png
│   ├── hero-distribution.jpeg
│   ├── crowd-bags.jpeg
│   ├── team-group.jpeg
│   └── school-visit.jpeg
└── README.md
```

## Running locally

No build tools needed. Either:

- Open `index.html` directly in a browser, or
- Run a local server from this folder, e.g.:
  ```bash
  python3 -m http.server 8000
  ```
  then visit `http://localhost:8000`

## Deploying

This is a static site, so it can be hosted for free on:
- **GitHub Pages** — Settings → Pages → deploy from the `main` branch
- **Netlify** / **Vercel** — drag-and-drop the folder or connect the repo
- Any standard static web host

## Editing

- Colors and fonts are defined as CSS variables at the top of the `<style>` block in `index.html`.
- The donate modal (bank details) is near the bottom of the file — update it there if account details change.
- To swap or add photos, drop new files into `images/` and update the `src` paths in `index.html`.

## Contact info currently on the site

- Phone: +234 805 580 0922 / +44 742 465 7037
- Email: garvininspired@gmail.com
- Address: Association Avenue, Governor's Road, Ikotun, Lagos State
- Website: garvininspired.org
