# Nomina MCP — product site

Static site for Nomina MCP (https://github.com/nomina-xyz/nomina-mcp), built in Nomina's design
system: Lay Grotesk / Onsite Mono, `#0b080a` base, `#a8ff99` accent, sharp corners, 1px strokes.
No build step — plain HTML/CSS/JS served by GitHub Pages.

- `index.html` — the page
- `assets/css/site.css` — tokens and components (values mirror nomina.io's stylesheet)
- `assets/js/site.js` — install tabs, copy buttons, mobile menu
- `assets/fonts/` — Lay Grotesk and Onsite Mono (Nomina's licensed web fonts, self-hosted)
- `assets/brand/` — Nomina mark, logotype and icon from the public brand kit

Staging hostname: `testing.nomina.io` (CNAME). The page carries `noindex` while on staging.

Local preview: `python3 -m http.server 8790` in this directory.
