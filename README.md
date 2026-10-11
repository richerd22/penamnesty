# penamnesty.cold.fyi

The Pens Went Away - a cited deep dive on pharmaceutical promotional merchandise (1990-2008), with a 440-piece sourced directory. Static site: no build step, no database, no upkeep.

## Files

- `index.html` - the whole site (article, timeline, quiz, pen generator, amnesty certificate, directory)
- `directory.json`, `directory.csv` - the directory as open data
- `fonts/` - self-hosted Archivo Narrow, Newsreader, IBM Plex Mono (SIL Open Font License)
- `og.png`, `favicon.svg`, `apple-touch-icon.png` - share image and icons
- `robots.txt`, `sitemap.xml`, `llms.txt` - search and AI-crawler discovery
- `CNAME` - tells GitHub Pages the custom domain
- `404.html` - "This page has been discontinued."

## Going live (one time)

1. GitHub: Settings → Pages → Build and deployment → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
2. Namecheap → cold.fyi → Advanced DNS → add a **CNAME Record**: Host `penamnesty`, Value `richerd22.github.io.`, TTL Automatic.
3. Back in GitHub Pages, confirm the custom domain reads `penamnesty.cold.fyi`, wait for the DNS check, then tick **Enforce HTTPS**.
4. Optional, for faster indexing: add the site in Google Search Console and submit `https://penamnesty.cold.fyi/sitemap.xml`.

## Notes

- Archive photos load from Wellcome Collection, the Library of Congress and the DEA, each credited under its license. If a host ever goes down, the page shows a credit card linking to the original instead of a broken image.
- Smithsonian and Science Museum photos are reuse-restricted, so the page links to them instead of embedding them.
- Researched October 2026. Prices are asking prices unless marked sold.

made with <3 in boston
