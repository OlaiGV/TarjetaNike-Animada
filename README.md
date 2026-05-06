# 👟 Nike Animated Card

[![Live Preview](https://img.shields.io/badge/Live%20Preview-GitHub%20Pages-0A66C2?style=for-the-badge&logo=github&logoColor=white)](https://olaigv.github.io/TarjetaNike-Animada/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

Interactive product card with a multi-step hover animation built with **pure HTML and CSS** — no JavaScript, no frameworks.

---

## 🖥️ Live Preview

> 👉 **[olaigv.github.io/TarjetaNike-Animada](https://olaigv.github.io/TarjetaNike-Animada/)**

| Default state | After hover |
|:---:|:---:|
| <img width="600" alt="Nike card idle" src="https://github.com/user-attachments/assets/c6747720-8eac-497b-b52a-662bedd7c39c" /> | <img width="600" alt="Nike card expanded" src="https://github.com/user-attachments/assets/290f7c5e-2e84-4e75-b702-6f8100beb08d" /> |

---

## ✨ Features

- 🎬 **Multi-layered hover animation** — circle → card expansion → product reveal
- 💡 **CSS glow effect** using `drop-shadow` filters
- 🖼️ **Product image** flies in with rotation on hover
- 🔘 **Reusable CTA button** component with its own CSS file
- ⚡ **Zero dependencies** — no JavaScript, no libraries
- ♿ **Accessible** — keyboard focus support and ARIA attributes

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic structure |
| CSS3 | Animations, transitions, glow, layout |
| Google Fonts | Courgette · Rubik Gemstones |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/OlaiGV/TarjetaNike-Animada.git

# Open in browser
cd TarjetaNike-Animada
open index.html
```

No build step or package manager needed.

---

## 📁 Project Structure

```
TarjetaNike-Animada/
├── index.html          # Main entry point
├── README.md
├── css/
│   ├── reset.css       # CSS reset
│   ├── styles.css      # Card & animation styles
│   └── button.css      # Reusable CTA button
└── images/
    ├── logo.png        # Nike logo
    └── nike.png        # Product image
```

---

## 🎨 Customization

Edit these values in `css/styles.css` to adapt the card to your brand:

```css
body {
  --clr: #ffffff; /* Glow color & card accent */
  background: #33333381; /* Page background */
}
```

Swap out the images inside `/images/` to use a different brand or product.

---

## 🌐 Browser Support

| Browser | Support |
|---|---|
| Chrome 88+ | ✅ |
| Firefox 85+ | ✅ |
| Safari 14+ | ✅ |
| Edge 88+ | ✅ |

---

## 📄 License

MIT License — free to use and adapt in your own projects.

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/OlaiGV">OlaiGV</a>
</div>

