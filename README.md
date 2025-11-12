# Esteban Portfolio (core)

This bundle contains the HTML/CSS/JS for the portfolio. It does **not** include the `assets/` folder.

## Files
- `index.html` – project grid (reads `projects.json`)
- `project.html` – detail page + 3D GLB viewer (Three.js + GLTFLoader)
- `projects.json` – project data (images/videos/models)
- `style.css` – theme
- `README.md` – this file

## Assets layout
```
assets/
  images/   (Airplane Model1.jpg, Antonov1.jpg, ...)
  videos/   (Fifth Mill Practice1.mp4, ...)
  models/   (AIR_PLANE_CLEAN.glb, Antonov.glb, Fifth Mill Practice.glb, ...)
```

## Add a new project
Edit `projects.json` and append a new object; spaces in file names are OK.
