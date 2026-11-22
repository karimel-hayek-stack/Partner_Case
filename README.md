# Partner Election Case: Karim El Hayek

Animated HTML presentation, built as a static site for GitHub Pages.

- `Index.html`: Energy & Utilities edition (main deck)
- `classic.html`: Classic edition

Everything (fonts, images, logos, animations) is embedded in each HTML file, so no build step or server is needed.

## Publish on GitHub Pages
1. Push these files to the root of a repository (keep `.nojekyll`).
2. Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
3. The deck is served at `https://<owner>.github.io/<repo>/` (classic edition at `/classic.html`).

## Controls
→ / Space: next (also reveals the end-of-slide animations) · ← back · N notes · T timer · P placeholders · L logo upload · F full screen.
Open at a given slide with `#N`, e.g. `.../#6`.
