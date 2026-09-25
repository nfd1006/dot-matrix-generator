# Dot Matrix — Logo Assembler

Upload a logo and watch it assemble from scattered dots into your silhouette — a self-contained, client-side tool. Nothing you upload leaves your browser.

## Features

- Auto-thresholding silhouette extraction (Otsu's method) with adjustable Threshold/Invert
- Fixed addressable backbone grid (adjustable resolution) — every dot has a stable normalized (x, y) position
- HSV color picker, LED-panel background grid, glow bloom
- Ripple / Sweep / Random assembly wave effects
- Idle breathing + a "Run Cycle" in-place jog animation
- Background: transparent, solid color, or image
- Export as PNG or WebM video (captures the full reveal animation)

## Run locally

Just open `index.html` in a browser — no build step, no dependencies.
