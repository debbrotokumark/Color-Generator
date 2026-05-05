# 🎨 PalettePro — Color Palette Builder

<div align="center">

![PalettePro Banner](https://img.shields.io/badge/PalettePro-Color%20Palette%20Builder-e8500a?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEycy40OCA5LjUyIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0tMSAxNy45M1Y0LjA3YzMuOTQuNDkgNyAzLjg1IDcgNy45M3MtMy4wNiA3LjQ0LTcgNy45M3oiLz48L3N2Zz4=)

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-debbrotokumark.github.io-blue?style=for-the-badge)](https://debbrotokumark.github.io/Color-Generator/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/debbrotokumark/Color-Generator)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A powerful, zero-dependency color palette builder for designers and developers.**

[Live Demo](https://debbrotokumark.github.io/Color-Generator/) · [Report Bug](https://github.com/debbrotokumark/Color-Generator/issues) · [Request Feature](https://github.com/debbrotokumark/Color-Generator/issues)

</div>

---

## ✨ Features

### 🖌️ Color Management
- **Add colors** by hex code, RGB, HSL, or the native color picker
- **Edit colors** in any format — HEX, RGB, or HSL — with live sync between all fields
- **Lock colors** to keep them safe when regenerating palettes
- **Favorite colors** to filter and highlight your picks
- **Delete** individual or multiple colors at once with **Select Mode**
- **Drag & drop** to reorder colors in the grid

### 🎲 Palette Generation
- **Random Palette** — instantly generate a fresh 6-color palette
- **Smart Palette** — generate harmonious palettes from a base color using:
  - Complementary
  - Analogous
  - Triadic
  - Split-Complementary
  - Tetradic
  - Monochromatic
  - Shades

### 🌈 Gradient Builder
- Select any colors from your palette and preview them as a CSS gradient
- Choose direction: Horizontal, Vertical, Diagonal, Corner, or Radial
- One-click copy of the generated CSS gradient code

### 📥 Import Colors
Import from 5 different sources:

| Source | Formats Supported |
|--------|------------------|
| **Text / HEX** | `#rgb`, `#rrggbb`, `rgb()`, `hsl()`, comma/space/newline separated |
| **JSON** | Array of hex strings or objects with `hex` property |
| **CSS** | CSS variables, inline styles, any CSS containing color values |
| **File** | `.json`, `.txt`, `.css`, `.scss` |
| **URL** | PalettePro share URLs |

> Supports **merge mode** — import into existing palette without losing your work.

### 📤 Export Palette
Export your palette in 7 formats:

| Format | Use Case |
|--------|----------|
| **JSON** | Full palette data with hex, RGB, HSL, locked & favorite state |
| **CSS Variables** | Ready-to-paste `:root {}` CSS custom properties |
| **Tailwind Config** | Drop into `tailwind.config.js` colors section |
| **SCSS Variables** | `$color-N: #hex;` for Sass/SCSS projects |
| **SVG** | Visual swatch sheet you can embed or open in Figma |
| **ASE / Plain** | Plain hex list for other tools |
| **Plain Text** | One hex per line |

### 🖼️ Image Color Extraction
- Drop or upload any image
- Automatically extracts the **top 8 dominant colors** using pixel sampling and color quantization

### 🔗 Share Palette
- Generate a **shareable URL** that encodes your entire palette
- Anyone with the link can open and import it instantly — no account needed

### 🔍 Search & Filter
- **Search** colors by hex value in real time
- **Filter** view by All / Favorites / Locked

### ↕️ Sort Colors
- By **Hue** — arrange colors around the color wheel
- By **Lightness** — dark to light or vice versa
- By **Saturation** — vivid to muted
- **Alphabetically** — by hex value

### ♿ Accessibility
- **WCAG contrast badge** on every color card (AA / AA Large / Fail)
- Contrast ratio shown against both white and black
- Color-coded contrast indicators

### 🕒 Other Features
- **Recent Colors** — quick-access history of the last 24 colors you added
- **Undo / Redo** — up to 60 steps of history (Ctrl+Z / Ctrl+Y)
- **Dark Mode** — toggle between light and dark theme, persisted to localStorage
- **Bulk Select Mode** — select multiple colors and delete them at once
- **Fully responsive** — works great on mobile and desktop
- **No dependencies** — pure HTML, CSS, and vanilla JavaScript; no npm, no build step

---

## 🚀 Getting Started

### Option 1: Use the Live Demo
👉 **[https://debbrotokumark.github.io/Color-Generator/](https://debbrotokumark.github.io/Color-Generator/)**

No installation required.

### Option 2: Run Locally

```bash
# Clone the repository
git clone https://github.com/debbrotokumark/Color-Generator.git

# Navigate into the project
cd Color-Generator

# Open in your browser
open index.html
# or just double-click index.html
```

> ✅ No build tools, no npm install, no server needed. It's a single HTML file.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `A` | Focus the hex input to add a color |
| `R` | Generate a random palette |
| `T` | Toggle dark/light theme |
| `Backspace` | Clear all colors |
| `Ctrl + Z` | Undo last action |
| `Ctrl + Y` | Redo last undone action |
| `Escape` | Close any open modal |

---

## 📸 Screenshots


| Light Mode | Dark Mode |
|-----------|-----------|
| ![Light](https://github.com/user-attachments/assets/c6c97436-7f6e-4c26-b14a-172be6e9b8e9) | ![Dark](https://github.com/user-attachments/assets/260a1c09-c657-4a16-9bc3-c177425be471) |

---

## 🛠️ Project Structure

```
Color-Generator/
└── index.html          # The entire app — all HTML, CSS, and JS in one file
```

This is intentionally a single-file app. No frameworks, no bundler, no build pipeline — just open and use.

---

## 🧩 How It Works

### Color Math
All color conversions (HEX ↔ RGB ↔ HSL) are implemented from scratch using standard formulas. Contrast ratios are calculated using the WCAG 2.1 relative luminance formula.

### Smart Palette Generation
Given a base HSL color, each harmony type shifts the hue by fixed degrees:
- **Complementary**: 180°
- **Analogous**: ±15°, ±30°
- **Triadic**: 120°, 240°
- **Tetradic**: 90°, 180°, 270°

### Image Color Extraction
Uses the HTML5 Canvas API to sample pixels from the uploaded image, quantizes RGB values into a 32-step grid, and returns the most frequent color buckets.

### State Persistence
The palette, history, and theme are all persisted to `localStorage` so your work survives page refreshes.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👤 Author

**Debbrotokumark**

- GitHub: [@debbrotokumark](https://github.com/debbrotokumark)
- Live Project: [debbrotokumark.github.io/Color-Generator](https://debbrotokumark.github.io/Color-Generator/)

---

<div align="center">

Made with ❤️ and a lot of colors

⭐ **Star this repo if you found it useful!** ⭐

</div>
