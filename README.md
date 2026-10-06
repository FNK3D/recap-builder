# 💠 RECAP Builder

> A standalone HTML widget for building portfolio grids: circle, diamond, 3×3 square, or shards. Exports to PNG, SVG, and HTML.

[![License: MIT](https://img.shields.io/badge/License-MIT-00ffcc.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)]()

---

## ✨ What is it?

**RECAP Builder** is a single-file HTML tool for creating beautiful portfolio recaps. Drop in your images, pick a shape, tweak the sliders — and export a ready-to-use widget for your website.

No installation. No build step. No dependencies. Just open the file in a browser.

---

## 🎨 Features

- **4 shapes** — Circle, Diamond (polygon), Square 3×3, Shards (Voronoi)
- **Drag & drop** images directly onto tiles, or bulk upload
- **Per-tile control** — pan, zoom, replace, reorder
- **3D tilt** on hover with adjustable depth
- **Curved text** along the ring (single line or top/bottom split)
- **8 fonts**, adjustable size, spacing, radius, color, and text band
- **Random sizes** mode for organic layouts
- **Crop-on-load** with 9 anchor positions
- **Undo / Redo** — up to 20 steps
- **Multi-language UI** — 8 languages (RU, EN, ES, DE, JA, ZH, FR, PT)
- **Export to PNG** (2000×2000, transparent), **SVG** (vector), **HTML** (standalone widget)
- **HTML export** includes optional JPEG compression + live weight counter
- **Embed code** generator for `<iframe>` integration

---

## 🚀 Usage

1. Download [`recap.html`](./recap.html)
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Load your images:
   - Click a tile to upload one image
   - Drag & drop files from your file manager
   - Or use **Upload works** for bulk loading
4. Choose a shape, adjust the sliders, add text
5. Click **Preview** to see the final result
6. Export as **PNG**, **SVG**, or **HTML**

That's it. The file works completely offline — no server, no internet required.

---

## 📦 Export formats

| Format | Description |
|---|---|
| **PNG** | 2000×2000, transparent background — perfect for social media |
| **SVG** | Vector — scales infinitely, editable in Illustrator/Figma |
| **HTML** | Fully standalone widget — one file, all images embedded as base64 |

The **HTML export** has a built-in compression setting:
- Original images: keep as-is
- Compressed: resize to max side (600–4000 px) + JPEG quality (50–95%)
- Live weight counter shows you the result before downloading

---

## 🖼️ Screenshots

> _Coming soon — add your own screenshots to `docs/` and reference them here._

---

## 🛠️ Tech

Pure vanilla **HTML + CSS + JavaScript**. No frameworks, no bundlers, no dependencies. Google Fonts loaded from CDN (optional — works offline with system fonts).

---

## 📜 License

MIT © 2026 [FNK3D](https://github.com/FNK3D)

Free to use, modify, and distribute. See [`LICENSE`](./LICENSE) for details.

---

## 🔗 Links

- **Author:** [FNK3D](https://github.com/FNK3D)
- **All links:** [taplink.cc/fnk3d](https://taplink.cc/fnk3d)