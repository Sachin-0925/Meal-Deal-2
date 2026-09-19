# Meal-Deal-2

Independent portrait restaurant TV signage for Hollick Kenyon. This project does not reference or modify Meal-Deal.

TV URL: https://sachin-0925.github.io/Meal-Deal-2/

## Operation

Open the URL in a fullscreen browser on a portrait display. Native layout: 1080 × 1920. Smaller or differently shaped browser windows scale the entire portrait composition proportionally. No interaction is needed after opening. Keep the TV/browser awake using its own display or kiosk settings.

Five rows show deals 1–5, then 6–10. Entrances start 1.4 seconds apart, animate for 650 milliseconds, and the completed group holds for 8 seconds. All five rows fade out together over 650 milliseconds, followed by a completely empty deal area for 1 second before the next group starts. Groups never mix. The first group also starts with an empty deal area for 1 second. The plain bold text header and footer stay fixed and visible, including during empty transitions. Reduced-motion preferences use a fade without sliding.

All imagery and the open-source Anton font are bundled locally. Food artwork is cropped from the approved Hollick Kenyon poster; only surrounding background and poster-border fragments were removed. No generated or substituted food imagery. The source poster's limited resolution determines the image detail.

## Files

- index.html — page structure
- styles.css — portrait layout and local font
- signage.js — approved deal data and continuous animation
- deal-*.png and meal-deal.png — original food cutouts and header artwork
- Anton-Regular.ttf and OFL.txt — bundled font and its license
- .nojekyll — plain static GitHub Pages delivery

There is no build step, backend, login, database, package install, or runtime external dependency. Open index.html locally for offline playback, or serve this folder with any static server.

## GitHub Pages

Settings → Pages → Deploy from a branch → main → / (root) → Save.
