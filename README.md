# Loopwash

Seamless, looping gradient backgrounds, exported as GIF or MP4. Everything runs in the browser from a single file: `index.html`.

## Use it

Open `index.html` in a current Chrome, Edge or Safari. Nothing needs installing. Exports save to your Downloads folder.

To host it, turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).

## What it does

- **Ten styles:** Linear, Radial, Conic, Fluid, Waves, Blobs, Arcs, Orbit, Shape and Fractal.
- **Shape:** upload an SVG, or drop it onto the preview, and it becomes a glowing spectrum that pulses or flows outward. Five built-in shapes (heart, star, arch, drop, circle) are included.
  - *Keep silhouette* draws every ring as a scaled copy of the shape. *Follow edge* draws rings at a fixed distance from the outline.
  - Shapes that can't be scaled cleanly from their center switch to *Follow edge* automatically.
- **Fractal:** soft color masses seen through fluted glass. The **Glass ribs** and **Refraction** controls work on every style.
- **Controls:** 2 to 6 colors, speed, loop length, size, angle, center, softness, distortion, blur and grain.
- **Presets:** start from built-in presets or save your own. Saved presets stay in the browser you made them in.
- **Seamless loops:** speed is a whole number of cycles per loop, so the last frame always flows into the first.
- **Export:**
  - GIF: up to 800 px, loops forever.
  - MP4 (H.264): up to 4K, with an option to repeat the loop several times in one file.

## Notes

- Fonts (Google Fonts) and the MP4 converter ([mp4-muxer](https://github.com/Vanilagy/mp4-muxer)) load from a CDN. Offline, the page falls back to system fonts, and MP4 export switches to a slower option that records in real time.
- GIFs are limited to 256 colors, so smooth gradients get a fine dither pattern. MP4 looks cleaner for most backgrounds.
