# Mini Games Website — Publish on GitHub Pages

This zip contains your arcade website, ready to go live.

## Files

- `index.html` — the entire website (all 28 games, fully self-contained)

## Publish in 5 minutes

1. Create a new repository on GitHub (e.g. `mini-games-website`). Make it **Public**.
2. Upload `index.html` to the repository root
   (web: Add file → Upload files, or `git push` from your computer).
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   choose the `main` branch and the `/ (root)` folder. Save.
5. Wait ~1 minute. Your site will be live at
   `https://<your-username>.github.io/<repo-name>/`.

## Notes

- The site works offline / on slow connections: every game is plain
  JavaScript bundled into the single file. The only online nicety is the
  Google Font, which gracefully falls back to system fonts without internet.
- Scores are per-visit (browser memory) and reset when the tab closes.
- To update the site later, just replace `index.html` and push again.
