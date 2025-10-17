LexVence — Repo-ready package from last good Netlify deploy

This folder mirrors your successful Netlify deployment to preserve layout/colors/UX exactly.

Files included:
- index.html
- sitemap.xml
- robots.txt
- netlify.toml  (configured with publish = ".")

How to use:
1) Create / open your GitHub repo (e.g., purple-flame-code/lexvence).
2) Put these files at the REPO ROOT (exactly as-is).
3) In Netlify → Build settings:
   • Build command: (leave empty)
   • Publish directory: .
4) Trigger deploy → Clear cache and deploy site.
