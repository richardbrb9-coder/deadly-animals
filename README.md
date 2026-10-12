# Deadly Animals 🐾

A fun, educational animal app for kids: an Animal-pedia of 127 deadly (and a few not-so-deadly) animals,
a World Map to explore who lives where, and games (Animal Pairs, Tiger Cub Rescue maze, Animal Quiz,
Who Am I? and Safari Dash).

## ▶️ [Open the app in your browser](https://richardbrb9-coder.github.io/deadly-animals/)

**https://richardbrb9-coder.github.io/deadly-animals/** works on a computer, tablet or phone. Nothing to download.

It's a Progressive Web App (PWA): once installed it works offline.

## Install on a tablet
1. Open [the app](https://richardbrb9-coder.github.io/deadly-animals/) while connected to the internet.
2. **iPad:** in Safari tap **Share → Add to Home Screen**. **Android:** in Chrome tap **Install app**.
3. Open it once from the home screen while still online, so every picture is saved for offline use.

## Updating
After changing the app, bump `CACHE_NAME` in `sw.js` (e.g. `v7` → `v8`) and push. Tablets pick up the
new version the next time the app is opened while online.

## Files
- `index.html` – the whole app (screens, games, styles)
- `animals.js` – the animal list, descriptions and clues
- `world-map.js` – the continent outlines for the World Map
- `animal-images/` – one WebP picture per animal (600 × 800)
- `sw.js` – the service worker that saves everything for offline use
- `manifest.json` – app name, icons and colours for installing
