# UNO_APP

A simple football mini-game turned into a browser-based app.

## Run locally

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## App features

- installable as a browser app (PWA)
- offline cache support via service worker
- score tracking and simple in-browser game loop
- audio toggle and install prompt support

## Files

- `index.html` — app shell and game logic
- `manifest.json` — install metadata
- `sw.js` — offline caching
- `icon.svg` — app icon
