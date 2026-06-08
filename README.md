# SENshine static draft site

Static noindexed draft site for SENshine Embrace. Links and assets use relative paths so the site works on GitHub Pages under `/SenTest0606/`.

## Protections

- `robots.txt` blocks all crawlers.
- Every HTML page includes `noindex,nofollow,noarchive`.
- Netlify `_headers` adds `X-Robots-Tag: noindex, nofollow, noarchive`.

No tracking scripts are embedded. Forms and quizzes open as external links.
