# Musubi — presentation site

Static landing page for **Musubi** (public brand of the KOTR platform):
a single self-contained `index.html`, no build step, no dependencies
beyond the Ubuntu webfont.

## Structure

- `index.html` — the whole site (styles and scripts inlined)
- `favicon.svg` — the awaji-knot mark (red cord on sand)

## Brand tokens

| Token | Value |
|---|---|
| Sand (background) | `#f4e7cd` |
| Paper (cards) | `#fdfaf3` |
| Ink (text) | `#3f2d1d` |
| Brown (headings) | `#7c3f21` |
| Red (accent, cord) | `#c1272d` |
| Dark (footer/B2B) | `#2a2119` |
| Font | Ubuntu 400/500/700 |

The loader plays the "knot tightening" animation: the two tails get
pulled sideways while the loops cinch — the awaji knot tightens the
more you pull, which is the brand tagline.

## Deploy

Copy the folder to any static host (nginx, Coolify static site,
GitHub Pages). No server-side code.

## Preview locally

```bash
python3 -m http.server 8090
```
# musubi
