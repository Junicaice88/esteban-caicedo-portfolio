# Esteban Caicedo – Engineering Portfolio (v2.3.4 → +Fifth Mill)

Static portfolio with CAD/CAE projects, interactive 3D models (<model-viewer>), and a mixed-media gallery (images/videos).

## Structure
assets/
  images/      # JPG/PNG preview images
  videos/      # MP4 clips for galleries
  models/      # GLB files for <model-viewer>
index.html     # Projects grid with cross-fade cards
project.html   # Project detail: description + model viewer + media slider
projects.json  # Projects metadata
style.css      # Styles (Tailwind-like tokens)

## Add a new project
1. Drop media into assets/images/ or assets/videos/ and the GLB in assets/models/.
2. Add the entry in projects.json. Use images: [...] for images or media: [...] if you mix/include videos.
3. Deploy to Netlify/Vercel or serve locally.

## Notes
- Cross-fade slider supports JPG/PNG and MP4. Videos are muted, inline, looped.
- <model-viewer> is loaded from unpkg; ensure HTTPS for hosting.
