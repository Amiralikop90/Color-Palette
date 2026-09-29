# 🎨 Color Palette Generator

> Create beautiful, harmonious color palettes instantly — copy HEX/RGB codes, lock colors, save favorites, and download as PNG.

<p align="center">
  <a href="https://amiralikop90.github.io/Color-Palette/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Online-success?style=for-the-badge" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/HTML5-Single_File-orange?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT License">
  <img src="https://img.shields.io/badge/Zero-Dependencies-brightgreen?style=for-the-badge" alt="Zero Dependencies">
</p>

---

## 📖 About

**Color Palette Generator** is a sleek, single-file web tool that generates beautiful, harmonious color palettes right in your browser. Each palette contains 5 colors, shown with their HEX and RGB codes, ready to copy with one click.

Whether you're a designer looking for inspiration, a developer picking colors for a project, or someone creating content for social media, this tool gets it done in seconds.

---

## ✨ Features

### 🎨 Palette Generation
- 🎲 **Random palettes** — generate beautiful 5-color palettes instantly
- 🔒 **Lock colors** — keep your favorite colors when generating new palettes
- ⌨️ **Space shortcut** — press `Space` for a new palette

### 📋 Copy & Export
- 📋 **Click any color** — copy its HEX and RGB to clipboard
- 📋 **Copy All** — copy the entire palette at once
- 💾 **Download PNG** — save the palette as an image with HEX codes

### ⭐ Save & History
- ⭐ **Favorites** — save up to 20 palettes (stored in `localStorage`)
- 📜 **History** — automatically keeps the last 20 palettes
- 🗑️ **Clear All** — remove all favorites with one click

### 🌐 Internationalization
- 🇮🇷 Persian (فارسی) — RTL
- 🇬🇧 English — LTR
- 🇨🇳 Chinese (中文) — LTR

### 🌙 Themes
- ☁️ **Cloud White** — soft, light, airy
- 🖤 **Matte Black** — deep, flat, no glare

### ⚡ Performance
- 🚀 **Zero backend** — everything runs in your browser
- 💾 **No tracking** — your data never leaves your device
- 📱 **Fully responsive** — mobile, tablet, desktop
- ♿ **Accessible** — ARIA labels, semantic HTML
- 🔍 **SEO-optimized** — meta tags, Open Graph, Twitter Cards, JSON-LD
- 📄 **Footer with license link** — [psoa.ir/licens.html](https://psoa.ir/licens.html)

---

## 🚀 Live Demo

👉 **[https://amiralikop90.github.io/Color-Palette/](https://amiralikop90.github.io/Color-Palette/)**

---

## 🛠️ How to Use

1. Open the live demo
2. A random 5-color palette is generated automatically
3. Click **🎲 New Palette** or press `Space` for a new one
4. Click the **🔒 lock icon** on any color to keep it
5. Click any color to copy its HEX/RGB
6. Click **📋 Copy All** to copy the whole palette
7. Click **⭐ Save** to add to favorites
8. Click **💾 Download PNG** to save as image

---

## 🎯 Use Cases

| Use Case | Description |
|----------|-------------|
| **Web Design** | Find color schemes for websites and apps |
| **Graphic Design** | Get color inspiration for posters, logos |
| **Social Media** | Pick colors for Instagram, Twitter posts |
| **Branding** | Explore color combinations for a brand |
| **UI/UX** | Choose colors for user interfaces |
| **Presentations** | Pick colors for slides and charts |

---

## 📦 Deploy on GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose **Branch:** `main` and **Folder:** `/ (root)`
5. Click **Save** — your site will be live at:
https://amiralikop90.github.io/Color-Palette/

text

---

## 🌍 Supported Languages

| Language | Code | Direction |
|----------|------|-----------|
| 🇮🇷 Persian | `fa` | RTL |
| 🇬🇧 English | `en` | LTR |
| 🇨🇳 Chinese | `zh` | LTR |

Language can be switched from the top bar — your choice is remembered across visits via `localStorage`.

---

## 🎨 Themes

- ☁️ **Cloud White** — soft, light, airy (default)
- 🖤 **Matte Black** — deep, flat, no glare

Toggle from the top-left button. Your preference is saved automatically.

---

## 📁 Project Structure
.
├── index.html # Entire app: HTML + CSS + JS in one file
├── robots.txt # Search engine crawler rules
├── sitemap.xml # URL list for search engines
├── LICENSE # MIT License
└── README.md # This file

text

> The entire application lives inside a **single `index.html`** — no build tools, no bundlers, no `node_modules`.

---

## 🧰 Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties for theming, CSS Grid
- **JavaScript (Vanilla)** — no frameworks, no libraries
- **Canvas API** — for PNG export
- **localStorage** — for favorites and history
- **GitHub Pages** — free static hosting

---

## 🔍 SEO Features

This project ships with production-grade SEO out of the box:

- ✅ Optimized `<title>` and `<meta description>`
- ✅ `hreflang` tags for multilingual content
- ✅ Open Graph (Facebook, LinkedIn, Telegram)
- ✅ Twitter Card (`summary_large_image`)
- ✅ JSON-LD structured data (`WebApplication` schema)
- ✅ Canonical URL
- ✅ `robots.txt` and `sitemap.xml`
- ✅ Google Search Console verified
- ✅ Semantic headings
- ✅ ARIA labels for accessibility

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Generate new palette |

---

## 💾 Data Storage

All data is stored locally in your browser:

- **Favorites** — key: `color_palette_favorites` (max 20)
- **History** — key: `color_palette_history` (max 20)
- **Theme** — key: `cp_theme`
- **Language** — key: `cp_lang`

No data is ever sent to any server.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features, additional languages, or UI improvements:

1. Fork the repository
2. Create your branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 🔮 Planned Features

- 🎯 **Color harmony modes** — Analogous, Complementary, Triadic, Monochromatic
- 🖼️ **Image color picker** — extract palette from uploaded image
- 📤 **Export formats** — CSS, SCSS, Tailwind config, JSON
- 🎨 **Gradient generator** — combine two colors into a gradient
- 🔍 **Color blindness simulator** — preview for accessibility
- 📱 **PWA support** — install as a mobile app
- 🌐 **More languages** — Arabic, Russian, Spanish, German, French
- 🖌️ **Adjustment tools** — tweak hue, saturation, lightness

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

See the [LICENSE](LICENSE) file for details.

For more information, visit the license page:
👉 **[https://psoa.ir/licens.html](https://psoa.ir/licens.html)**

---

## 👤 Author

**Amirali Kamani**

- 🌐 Website: [psoa.ir](https://psoa.ir)
- 💻 GitHub: [@Amiralikop90](https://github.com/Amiralikop90)
- 📜 License page: [psoa.ir/licens.html](https://psoa.ir/licens.html)

---

<p align="center">
  Made with ❤️ — because beautiful colors should be one click away.
</p>
