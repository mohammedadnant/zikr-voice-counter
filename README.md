# Zikr Voice Counter

A free, open-source browser-based Zikr counter with microphone speech recognition and manual counting.

## Features
- Common Arabic Zikr presets and custom phrases
- Manual +1, undo and reset
- Adjustable target and progress indicator
- Browser speech recognition (Arabic, English, Urdu and Hindi options)
- Local counter persistence (localStorage)
- Mobile-friendly interface

## Run locally

```bash
npm install
npm run dev
```

Build with `npm run build`.

## Limitations
Speech recognition support varies by browser and device. Chrome/Edge are recommended. Microphone access requires HTTPS or localhost. Speech recognition may use a browser vendor's cloud service; do not assume it is offline. The app does not send audio to its own server. Recognition may miss or incorrectly count phrases. Background listening is not supported.

## Hosting
Deploy the `dist/` build to a static host. For GitHub Pages under a repository subpath, configure the Vite base path first.

## Privacy
Only count, target and selection are stored locally in the browser. Clearing site data resets them.

Deployment retry: GitHub Pages configured for GitHub Actions.
