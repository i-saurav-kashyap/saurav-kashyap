# Saurav Kashyap — Portfolio

Personal engineering portfolio. **Software Engineer II** building field asset management,
connectors, integrations, and CI/CD for enterprise SaaS (telecom · energy · infrastructure).

> Design direction: **"Control Plane"** — the site treats a career as a system you operate.
> Instrument-grade dark UI, a bi-accent signal system (cyan = live flow, amber = recognition),
> and a signature career signal-graph. Type: Space Grotesk · IBM Plex Sans · IBM Plex Mono.

## Run locally

No build step. Open `index.html` directly, or serve it:

```bash
python3 -m http.server 8080   # then visit http://localhost:8080
```

## Deploy (GitHub Pages)

Settings → Pages → **Deploy from a branch** → `main` / root. Site is fully static.

## Structure

```
index.html              # single-page site
assets/css/styles.css   # design system + components
assets/js/app.js         # scroll reveal, nav, scroll-spy, reduced-motion gating
assets/docs/             # résumé (PDF)
assets/img/              # project thumbnails (WebP UI screenshots)
```

## Projects section

The `#projects` section showcases live web apps, ordered **corporate → developer tools →
learning/general**. Each card links to its live Netlify deployment (repos are intentionally not
linked). The two JSON↔Apex converters are cross-linked as alternative builds. Thumbnails are real
UI screenshots captured headless (Chrome DevTools Protocol) and stored as WebP. To refresh a
thumbnail, re-screenshot the site at 1280×800 and export WebP into `assets/img/<slug>.webp`.

## Roadmap

- [x] Fill impact metrics in Experience (20% sales-process efficiency)
- [x] Confirm which Architect/AI badges to publish — all 9 certs are earned
- [ ] Replace draft Engineering Philosophy notes with own words
- [ ] Phase 2: migrate to Astro + MDX for Case Studies & Technical Writing
- [ ] Optional: light-mode theme

## Links

[LinkedIn](https://www.linkedin.com/in/saurav21/) · [GitHub](https://github.com/i-saurav-kashyap) · urskashyap21@gmail.com
