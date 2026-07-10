# Sughero Systems — landing page

Static single-page site. No build step, no dependencies.

## Structure

- `index.html` — all content and a small scroll-reveal script (respects reduced-motion)
- `styles.css` — all styling
- `assets/kathryn.jpg` — **placeholder**; replace with Kathryn's monochrome portrait (~800×800)

## Before deploying

1. Replace `assets/kathryn.jpg` with the real portrait.
2. Swap `contact@sugherosystems.com` in `index.html` (two places: the `mailto:` href and the visible text) for the real address.

## Deploy (Netlify)

Push the folder to GitHub, then in Netlify: **Add new site → Import from Git**, no build command, publish directory = repo root. Or drag the folder onto the Netlify dashboard.
