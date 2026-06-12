# AI Narrative Radar

Static GitHub Pages site for a daily AI narrative radar.

- `index.html`: mobile-friendly home page and archive index
- `latest.html`: fixed entry that redirects to the newest daily issue
- `daily/YYYY-MM-DD.html`: daily archive pages
- `assets/styles.css`: shared responsive styling

Daily automation should generate a new `daily/YYYY-MM-DD.html`, update
`latest.html`, update the archive list in `index.html`, then commit and push.
