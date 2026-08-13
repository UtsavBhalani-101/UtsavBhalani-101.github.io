# Utsav Bhalani — Portfolio

Single-file personal academic/research portfolio.

## Structure

- `index.html` — single page with embedded CSS and fonts

Sections: Hero, Bio, Research (3 entries), Updates, Footer.

## Open locally

Directly in a browser:
```bash
open index.html
```

Or via a local server (optional, for font loading with full CORS):
```bash
python -m http.server 8000
```

## Design notes

- CSS variables in `:root` for easy retheming
- Font pair: Inter (body) + Cormorant Garamond (display)
- Accent color: `#7a5c3a` (warm brown, not generic blue)
- Mobile responsive, light theme only, no animations or JS dependencies
