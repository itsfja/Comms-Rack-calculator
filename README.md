# Comms-Rack-calculator

A shiny little calculator for working out how many rack units (U) your networking kit needs in a 10-inch rack — with a live elevation view that fills as you add devices, and a per-device patch/jack panel allowance for front-panel jacking.

**Live site:** <https://itsfja.github.io/Comms-Rack-calculator/>

## Features
- Live rack elevation (4U–12U) that fills bottom-up as kit is added
- Jack/patch panel allowance (0–2U) per device, rendered as its own slot in front of each device
- Catalogue of common kit: switches, router/firewall, patch panel, NVR, UPS, PDU, media converter, shelf, fan tray
- Custom device entry (any name, 1–4U)
- Live stats: Used U, Free U, utilisation %, device count, over-capacity warnings
- Build state persists in the browser (localStorage); Print/PDF export; Reset

## Run locally
`index.html` is fully self-contained — open it in any browser. No build step, no dependencies.

## Enabling GitHub Pages
Settings → Pages → Source: **Deploy from a branch** → Branch: `main`, folder: `/` (root).
