# Amgad Samir Sharkawy — Personal Profile

A bilingual (English / Arabic) personal profile page for **Amgad Samir Sharkawy** — journalist,
pianist, and content creator. Built as a single static HTML page and published with GitHub Pages.

**Live site:** https://amgadsamir498.github.io/

## What's inside

- `index.html` — the entire page (content + styles + a small amount of JavaScript)
- `assets/amgad-portrait.jpg` — hero portrait
- `assets/og.jpg` — social sharing image (1200 × 630)
- `assets/qr-website.png` — QR code in the Connect section (opens the previous website)
- `assets/favicon.svg` — browser icon
- `assets/apple-touch-icon.png` — iOS home-screen icon
- `404.html` — custom not-found page
- `robots.txt`, `sitemap.xml` — search engine basics
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Preview locally

Open `index.html` directly in a browser, or serve it locally:

```powershell
python -m http.server 8000
```

Then visit http://localhost:8000.

## Editing

All text lives in `index.html`. The page has three main sections:

1. **Hero** — photo, name, roles, short intro, and social icons
2. **The Story** — English bio and the three content pillars
3. **بالعربية** — the Arabic bio, set right-to-left

To swap the photo, replace `assets/amgad-portrait.jpg` with another 4:5 image (for example
716 × 896) and keep the same filename. For link previews, replace `assets/og.jpg` with a
1200 × 630 image.

## Publishing

The site is served from the `main` branch of the `AmgadSamir498.github.io` repository.
Any push to `main` updates the live site within a minute or two.
