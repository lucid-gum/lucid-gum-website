# Lucid — takelucid.co

Static site. Every page is fully self-contained (fonts + images inlined).

- `index.html` (desktop home) ↔ `mobile.html` (mobile home)
- `science.html` ↔ `science-mobile.html`
- `shop.html` ↔ `shop-mobile.html`

Desktop pages redirect to their mobile version under 700px wide; mobile pages redirect back at 900px+.
`favicon/` and `favicon.ico` are kept as real files for browsers/crawlers that request them directly.

## Deploy (overwrite existing repo)
1. Delete the old files in the GitHub repo.
2. Upload everything in this folder to the repo ROOT (index.html at top level).
3. Commit — Vercel auto-deploys from `main`.
