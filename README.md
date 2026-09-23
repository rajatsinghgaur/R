# GOTHAM AR — Live Face Filters

A browser-based live AR prototype using camera access, MediaPipe Face Landmarker, and Three.js/WebGL.

## Included
- Live camera start after explicit user action
- Real-time single-face tracking
- Five Batman-inspired procedural 3D filters
- Gotham skyline, searchlights, HUD, scanlines and reticle
- Filter switching
- Mirror toggle
- Camera stop button
- Responsive mobile layout

## Run locally

Camera access should be tested from localhost or HTTPS.

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## GitHub Pages

The project is a static site and can be deployed from GitHub Pages. Enable Pages for the repository's `main` branch and root folder.

## Technical stack
- MediaPipe Tasks Vision / Face Landmarker
- Three.js
- WebRTC getUserMedia
- WebGL

## Production notes
Pin/self-host CDN dependencies and the MediaPipe WASM/model assets before production deployment. Test frame rate and camera behavior on target mobile devices.

The visual treatment is Batman-inspired. Use official Batman logos, character artwork, film assets, or other protected brand material only where you have the required rights.
