# Maison Dorée — 3D Web Application
## H7006 Web 3D Applications — University of Sussex 2025/26

---

## Project Structure

```
assignment/
├── index.html          ← Main 3D app (menu + about page)
├── submission.html     ← Submission details & links
├── README.md           ← This file
└── models/
    ├── Croissant.glb
    ├── Cup Coffee.glb
    └── Chocolate Chip Cookie.glb
```

## How to Run Locally

1. Open the `assignment/` folder in **Visual Studio Code**
2. Install the **Live Server** extension (if not already installed)
3. Right-click `index.html` → **Open with Live Server**
4. The app will open at `http://127.0.0.1:5500/index.html`

> **Note:** The Three.js GLTFLoader requires a local server to load GLB files.
> Opening `index.html` directly as a file (`file://`) will cause CORS errors.
> Always use Live Server or upload to the Sussex ITS web server.

## Uploading to Sussex ITS Web Server

1. Connect to `unix.sussex.ac.uk` via **WinSCP** (SFTP)
2. Navigate to your `public_html/` directory
3. Upload the entire `assignment/` folder
4. Set folder permissions to **2755** (octal) via WinSCP → Properties
5. Access at: `https://users.sussex.ac.uk/~[yourusername]/assignment/`

## Features

- ✅ Three.js r158 with ES Modules
- ✅ GLTFLoader — loads real GLB 3D models
- ✅ OrbitControls — drag to rotate, scroll to zoom
- ✅ Wireframe toggle (required by brief)
- ✅ Main lighting toggle
- ✅ Warm accent lighting toggle
- ✅ Spin animation via JavaScript onClick
- ✅ Camera reset button
- ✅ Model selector UI (3 models)
- ✅ Content swapping (Menu / About pages)
- ✅ Responsive layout (mobile breakpoint at 900px)
- ✅ About page with full documentation
- ✅ submission.html
- ✅ Accessibility (ARIA, keyboard nav, reduced-motion)

## Technologies

- HTML5, CSS3, JavaScript ES6 Modules
- Three.js r158 (CDN via jsDelivr)
- GLB / GLTF 2.0 models
- CSS Grid layout
- Google Fonts (Playfair Display, DM Mono, Cormorant Garamond)

## References

- Three.js: https://threejs.org (MIT)
- GLTFLoader: https://threejs.org/docs/#examples/en/loaders/GLTFLoader
- OrbitControls: https://threejs.org/docs/#examples/en/controls/OrbitControls
- Google Fonts: https://fonts.google.com (OFL)
- Croissant model: [Add source here]
- Cup Coffee model: [Add source here]
- Chocolate Chip Cookie model: [Add source here]
