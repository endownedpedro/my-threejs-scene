# Yin · Yang — interactive 3D walkthrough

An interactive Three.js walkthrough of the Yin–Yang Intellectual & Social Space, a 7.70 × 7.80 m seminar room at Baze University, Abuja, designed by **D’axis Nebular** (ARC 818).

## Files

| File | What it is |
|---|---|
| `index.html` | Full walkthrough for computers: real textures, ambient occlusion, bloom, photo views with a compare slider, and the walkthrough film |
| `mobile.html` + `mobile.js` | Phone version: the 3D engine is bundled into one local script (no CDN, works on older iPhone and Android browsers), about 330 KB compressed |
| `photo_*.jpg` | The three photoreal renders used by the phone version's photo views |
| `walkthrough.mp4` | The 1 min 18 s photoreal walkthrough film (720p), played from both pages |

The full version loads Three.js 0.170 from the jsDelivr CDN; the phone version carries its own copy in `mobile.js`. Both pages have a **Menu** button to return from the room to the welcome screen.

## Controls

- **Computer:** W A S D or arrow keys to move, drag to look, double-click the floor to walk there, P near a gold marker for the render.
- **Phone:** drag the gold circle to walk, drag elsewhere to look, double-tap the floor to walk there.

## Publish with GitHub Pages

Settings → Pages → Source: **Deploy from a branch**, Branch: **main** / **(root)** → Save.
The site then opens at `https://<your-username>.github.io/my-threejs-scene/` with no login, and the phone version at `…/my-threejs-scene/mobile.html`.

---
D’axis Nebular · Lokogoma, FCT, Abuja · daxisnebular@yahoo.com · +234 813 522 0509
