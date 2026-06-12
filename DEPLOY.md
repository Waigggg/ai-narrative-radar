# Deploy to GitHub Pages

This workspace is ready to publish as a public GitHub Pages site.

1. Create a public GitHub repository named `ai-narrative-radar`.
2. Add the remote and push:

```sh
git remote add origin https://github.com/<your-github-username>/ai-narrative-radar.git
git push -u origin main
```

3. In GitHub, enable Pages from `main` branch and `/ (root)`.
4. Open the site:

```text
https://<your-github-username>.github.io/ai-narrative-radar/
```

After the remote is configured, the daily Codex automation can commit and push
new issues automatically. Until then, it can still generate and commit local
daily pages, but publication is blocked on the remote URL.
