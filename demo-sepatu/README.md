# Strydex — Sneaker Landing Page (demo)

Static landing page for a fictional running-shoe brand, built as a design and animation exercise. No build step: plain HTML, CSS and JavaScript.

## Features

- Hero with staggered blur-in entrance, wiped headlines and pulse rings
- Running / Training / Lifestyle collections with animated product switching
- 360° Studio: real 3D model you can rotate by hovering (mouse) or dragging (touch)
- Cart drawer, search, account (demo), customiser with monogram, lookbook stories
- Responsive layout for desktop, tablet and phone; respects `prefers-reduced-motion`

## Run locally

Open `index.html` in a browser. An internet connection is needed for Google Fonts and the 3D viewer ([model-viewer](https://modelviewer.dev/)).

## Deploy to Vercel

Import this repository in Vercel and keep the defaults:

- Framework Preset: **Other**
- Build Command: *(empty)*
- Output Directory: *(empty, repository root)*

## Credits

- Shoe photos: Bifty, [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Saysh-track-spike-red.png), CC BY 4.0. Backgrounds removed.
- 3D model "Materials Variants Shoe": © 2021 Shopify, [KhronosGroup glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/MaterialsVariantsShoe), CC BY 4.0. Stored base64-encoded in `assets/sepatu-3d.js` so the page also works when opened from disk.
- "Strydex" is a fictional brand.
