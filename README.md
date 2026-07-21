# Lucid — takelucid.co

Static site. `index.html` = desktop (redirects to `mobile.html` under 700px wide);
`mobile.html` = mobile (redirects back to `index.html` at 900px+).
Both are fully self-contained (fonts + images inlined). The `favicon/` folder and
`favicon.ico` are kept as real files so browsers/crawlers that request them directly get one.

## Deploy (overwrite existing repo)
1. Delete the old files in your GitHub repo.
2. Upload everything in this folder to the repo ROOT (index.html at top level).
3. Commit — Vercel auto-deploys from the connected branch.
