
# 🤖 Rover — Mechanical Arm + Mecanum Wheels

> A Fusion 360 design of a rover featuring a **robotic mechanical arm** and **mecanum wheels** for omnidirectional movement. Free to use in your projects, websites, and builds.

---

## 📸 Preview

![Rover Preview]((rover-preview.png))



---

## 📁 Files Included

| File | Format | Description |
|------|--------|-------------|
| `source/rover.f3d` | Fusion 360 | Original editable source file |
| `exports/rover.dxf` | DXF | 2D drawing — import into CAD tools, laser cutters, etc. |
| `exports/rover.stl` | STL | 3D mesh — use with web viewers, slicers, or 3D printing |

---

## ✨ Features

- 🦾 **Mechanical Arm** — Multi-joint arm for pick-and-place or interaction tasks
- 🔄 **Mecanum Wheels** — Allows full omnidirectional movement (forward, sideways, diagonal)
- 📐 Designed in **Autodesk Fusion 360**
- 🌐 Export-ready for web, print, and fabrication

---

## 🌐 Use on a Website

### Embed as an Image (PNG)

```html
<img src="https://raw.githubusercontent.com/rushikeshtimkikar/rover-fusion/main/exports/rover-preview.png" alt="Rover with Mechanical Arm and Mecanum Wheels" width="600" />
```

---

### Interactive 3D Viewer (STL via model-viewer)

Add a spinning, interactive 3D model to your website in just a few lines:

```html
<!-- Add this script to your <head> -->
<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

<!-- Add this where you want the 3D viewer -->
<model-viewer
  src="https://raw.githubusercontent.com/rushikeshtimkikar/rover-fusion/main/exports/rover.stl"
  alt="Rover with Mechanical Arm and Mecanum Wheels"
  auto-rotate
  camera-controls
  style="width: 100%; height: 500px;"
></model-viewer>
```

> ✅ Works in all modern browsers. No extra dependencies needed beyond the script tag.

---

### Embed 2D Drawing (DXF → SVG conversion)

To use the DXF as an SVG on the web:
1. Convert `rover.dxf` to `.svg` at [cloudconvert.com](https://cloudconvert.com/dxf-to-svg)
2. Host the SVG in your repo or CDN
3. Embed with:

```html
<img src="rover.svg" alt="Rover 2D Drawing" />
<!-- or inline for styling control -->
<object data="rover.svg" type="image/svg+xml" width="600"></object>
```

---

## 🛠️ How to Edit

1. Download `source/rover.f3d`
2. Open **Autodesk Fusion 360** (free for personal use)
3. `File` → `Open` → select the `.f3d` file
4. Modify freely — the design is fully parametric

---

## 📦 How to Download

**Clone the repo:**
```bash
git clone https://github.com/rushikeshtimkikar/rover-fusion.git
```

**Or download directly:**
> Click the green **Code** button → **Download ZIP**

---

## 🤝 Contributing

Got improvements? Fork the repo, make your changes, and open a pull request. All contributions welcome — improved arm design, wheel assembly tweaks, new export formats, etc.

---

## 📄 License

This design is released under the **MIT License** — free to use, modify, and distribute in personal and commercial projects. Credit appreciated but not required.

---

## 👤 Author

**Rushikesh Timkikar**
GitHub: [@rushikeshtimkikar](https://github.com/rushikeshtimkikar)

---

*Built with ❤️ in Autodesk Fusion 360*
