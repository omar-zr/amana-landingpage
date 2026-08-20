# amana-landingpage

Landing page for **أمانة Amana** — a sealed medical tender platform connecting hospitals and laboratories with suppliers. The lowest compliant bid wins, and every decision is on the record.

**كل مناقصة موثَّقة. · Every tender, on the record.**

## Structure

- `index.html` — **V1**: the classic landing page. Clean, editorial, registry-paper aesthetic.
- `v2.html` — **V2**: the cinematic version. Dark hero, 3D mouse-tilt product mock, spinning seal coin, split-flap countdown, scroll-reveal animations, role marquee, and a SEALED stamp animation. Respects `prefers-reduced-motion`.

Both are self-contained (single file, inline CSS/JS), Arabic-first RTL with a full English toggle (`EN` button in the header). Fonts load from Google Fonts (IBM Plex Sans Arabic + IBM Plex Mono).

## Preview locally

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

Any static host works. For GitHub Pages: repo **Settings → Pages → Deploy from branch → `main` / root**.

## Brand

Follows the Amana brand identity v1.0: Seal Green `#0B3A31`, Copper `#A9662A`, Registry `#EDEDE7`, the seal mark, Arabic-primary script strategy, and Western digits in both languages.
