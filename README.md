# ✨ CSS Animation Collection 🎨

[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Pure CSS](https://img.shields.io/badge/Dependencies-Zero%20JS-brightgreen?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> A curated library of modern, lightweight, high-performance **Pure CSS** animations, glowing hover effects, and modern CSS `@property` experiments. Designed to bring web interfaces to life with zero JavaScript overhead! 🚀

---

## 📚 Table of Contents
- [🌟 Key Features](#-key-features)
- [🎨 Animation Catalog](#-animation-catalog)
  - [1. Rainbow Glowing Button](#1-rainbow-glowing-button)
  - [2. Animated Conic Border Card](#2-animated-conic-border-card)
- [📂 Repository Structure](#-repository-structure)
- [⚡ Quick Start](#-quick-start)
- [💻 Modern CSS Techniques Used](#-modern-css-techniques-used)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🌟 Key Features

- ⚡ **100% Pure CSS**: Zero external libraries or JavaScript required.
- 🎨 **Modern Aesthetics**: Vibrant rainbow gradients, dark-mode sleek styling, multi-layer glow effects.
- 🚀 **Next-Gen CSS Features**: Built with custom properties using `@property` for ultra-smooth angle transitions.
- 📱 **Fully Responsive**: Crafted with modern flexbox layouts and flexible box sizing.
- 🔌 **Plug & Play**: Modular snippet organization — ready to copy into any web project!

---

## 🎨 Animation Catalog

### 1. Rainbow Glowing Button 🔘
A smooth, interactive dark-themed button featuring an animated multi-color gradient glow on hover.

- 📁 **Source Code**: [`animate button/`](file:///d:/gouranga/code/web%20dev/css/all%20animation%20css/animate%20button/)
  - [`index.html`](file:///d:/gouranga/code/web%20dev/css/all%20animation%20css/animate%20button/index.html)
  - [`style.css`](file:///d:/gouranga/code/web%20dev/css/all%20animation%20css/animate%20button/style.css)
- ✨ **Key Highlights**: Multi-stop linear gradient, `filter: blur()`, CSS `@keyframes glowing`, multi-pseudo element layers (`::before` & `::after`).

```css
/* Quick Snippet Preview */
@keyframes glowing {
  0%   { background-position: 0 0; }
  50%  { background-position: 400% 0; }
  100% { background-position: 0 0; }
}
```

---

### 2. Animated Conic Border Card 🎴
A glowing card component with a 360° rotating rainbow spectrum border powered by modern CSS `@property`.

- 📁 **Source Code**: [`animate-border/`](file:///d:/gouranga/code/web%20dev/css/all%20animation%20css/animate-border/)
  - [`index.html`](file:///d:/gouranga/code/web%20dev/css/all%20animation%20css/animate-border/index.html)
  - [`style.css`](file:///d:/gouranga/code/web%20dev/css/all%20animation%20css/animate-border/style.css)
- ✨ **Key Highlights**: `@property --angle` registration, `conic-gradient`, smooth continuous rotation without Javascript, dual-layer backdrop glow.

```css
/* @property Enables Animating Custom Angle Variable */
@property --angle {
  syntax: "<angle>";
  initial-value: 0deg;
  inherits: false;
}
```

---

## 📂 Repository Structure

```tree
css-all-animation-learning/
│
├── 📁 animate button/
│   ├── index.html        # HTML structure for the glow button
│   └── style.css         # Multi-layer glowing hover keyframes
│
├── 📁 animate-border/
│   ├── index.html        # Card container setup
│   └── style.css         # Modern @property conic-gradient spin
│
└── 📄 README.md          # Project documentation
```

---

## ⚡ Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/all-animation-css.git
   ```

2. **Open any showcase in your browser**:
   Navigate to any animation folder and open the `index.html` file in your favorite web browser, or launch it using VS Code **Live Server**.

3. **Use in your own project**:
   Copy the HTML structure and relevant CSS styles directly into your design system or stylesheet.

---

## 💻 Modern CSS Techniques Used

| Feature | Description | Browser Support |
| :--- | :--- | :--- |
| **`@property` API** | Registers custom CSS variables for proper interpolation (e.g. animating `<angle>`) | All Modern Browsers |
| **`conic-gradient()`** | Renders color transitions rotated around a center focal point | Baseline Widely Available |
| **`filter: blur()`** | Creates realistic ambient light & neon glow effects behind pseudo-elements | Baseline Widely Available |
| **Pseudo-elements** | Utilizes `::before` & `::after` to create non-intrusive glow layers without polluting HTML structure | Universal |

---

## 🤝 Contributing

Contributions are always welcome! Feel free to:
1. Fork the repo 🍴
2. Create a feature branch (`git checkout -b feature/cool-new-animation`)
3. Commit your changes (`git commit -m 'Add modern glassmorphic card animation'`)
4. Push to the branch (`git push origin feature/cool-new-animation`)
5. Open a Pull Request 🚀

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

<p center align="center">
  Crafted with ❤️ and CSS magic ✨
</p>
