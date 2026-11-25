# Studiora PWA – hosting & install

Files (keep all in the SAME folder):
index.html, manifest.json, service-worker.js, icons/ (4 PNGs)

## Deploy on GitHub Pages (HTTPS, free)
1. Create a GitHub repo (e.g. `studiora`), public.
2. Upload index.html, manifest.json, service-worker.js and the icons folder to the repo root (Add file > Upload files; keep the icons/ folder).
3. Settings > Pages > Source: "Deploy from a branch", Branch: main, folder: / (root) > Save.
4. After ~1 minute open https://YOUR-USERNAME.github.io/studiora/

## Install on Android Chrome
1. Open the HTTPS URL in Chrome (not a file:// copy, not an in-app browser).
2. Wait a few seconds, then tap "⬇ Install App" in Studiora (or Chrome menu ⋮ > Install app).
3. Confirm the native dialog.

## Updating later
Change `CACHE_VERSION` in service-worker.js (e.g. studiora-v2) whenever you edit index.html.
