# Centered Life Counseling

A modern single-page website for Danielle Kashaija, LCSW. It highlights telehealth services, specialties, and impact stats, features a floating logo, a five-slide testimonial hero carousel, and anchored navigation tuned for a floating header.

## Preview locally
1. Open `index.html` directly in your browser, or
2. From this directory on macOS: `open -a "Safari" index.html`

## Structure
- `index.html` – Content and layout
- `styles.css` – Theme, layout, hero slider, responsive tweaks
- `assets/` – Logo (`DBK_Logo.png`, `logo-square.png`), about photo (`dbk_about.png`)

## Notes
- In-page links use `scroll-margin-top: 300px` to avoid the floating logo overlap.
- Hero slider auto-rotates every 7.5s; images are people-first and labeled with names.

## To adjust
- Logo position/size: edit `.floating-logo` in `styles.css`
- Hero height or interval: edit `.slider` height and the interval in the inline script near the end of `index.html`
- Brand font: `Great Vibes` loaded via Google Fonts in the document head

## Deployment
Any static host works (GitHub Pages, Netlify, Vercel). No build step required.
