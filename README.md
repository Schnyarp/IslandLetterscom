# IslandLetters.com

Static site hosted on **GitHub Pages** and fronted by **Cloudflare**.

## Status
**Coming Soon** — initial placeholder landing page while the archive is being built.

## Local development
Open `index.html` directly in a browser, or run a tiny static server:

```bash
python3 -m http.server 8080
```

Then visit:
- `http://localhost:8080/`

## Deployment
- Push to the branch that GitHub Pages is configured to publish (often `main`).
- Cloudflare handles the custom domain (`islandletters.com`).

## Notes
- During development the site may be protected with **Cloudflare Access** (email one-time PIN).
- When ready to launch publicly, disable/remove the Access application in Cloudflare Zero Trust.