# Kashaija Therapy Site

A modern single-page website for Danielle Kashaija, LCSW. It highlights telehealth services, specialties, impact stats (with live links), and features a hero testimonial carousel plus a floating header with full-width banner.

## Versions
- **Root**: Desktop-first layout with responsive tweaks.
- **mobile-friendly/**: Copy of the site with additional mobile optimizations (stacked header/nav, single-column hero on small screens, reduced paddings, shorter banner).

## Preview locally
1. Open `index.html` directly in your browser, or
2. macOS: `open -a "Safari" index.html`
3. For the mobile-friendly version: `open -a "Safari" mobile-friendly/index.html`

## Structure
- `index.html`, `styles.css` — main site
- `mobile-friendly/` — mobile-optimized clone (uses same assets)
- `assets/` — logo(s), about photo, toolkits, PDFs
  - `grounding-toolkit.md`
  - `sleep-hygiene-toolkit.md`
  - `sleep-hygiene-kids.pdf`, `sleep-hygiene-teens.pdf`, `sleep-hygiene-adults.pdf`

## Impact stats (live linked)
- Youth persistent sadness/hopelessness (CDC YRBS 2023) and adolescent MH prevalence (NSCH 2023)
- Adult depression prevalence (CDC 2024)
- PTSD annual prevalence (NIMH)
- Youth ADHD prevalence (CDC ADHD data)

## Deployment
Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). No build step required.
