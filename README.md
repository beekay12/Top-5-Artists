# 🎵 Top 5 — Rotation

An interactive, sleek web application displaying a curated list of top music artists and their signature tracks. Built with dynamic CSS vertical expansion, fluid variable typography, custom artist accent themes, and full keyboard navigation.

---

## ✨ Features

* 🎨 **Dark Slate Aesthetic** — Replaced traditional earthy tones with a crisp, modern charcoal/slate palette (`#0f1115`).
* 🔠 **Variable Typography** — Dynamic weight and optical size transitions powered by *Fraunces* serif variable font.
* 🌈 **Artist Accent Themes** — Distinct highlight colors customized per artist card.
* ⌨️ **Keyboard Navigation** — Seamlessly navigate between artists using `ArrowUp` and `ArrowDown` keys.
* 🔗 **Deep Linking** — Direct hash URL support (e.g., `#yeat`, `#kendrick`) to quickly jump to specific expanded views.
* 📱 **Mobile & Touch Friendly** — Touch-optimised flex layout with scroll lock handling (`overscroll-behavior: contain`).

---

## 🛠️ Built With

* **HTML5** — Semantic structure with full accessibility (`aria-expanded`, `aria-controls`)
* **CSS3** — Custom properties, CSS grid/flexbox, transitions, and `clamp()` dynamic scaling
* **JavaScript (ES6+)** — Keyboard shortcuts, history manipulation, and DOM interaction

---

## 🚀 Getting Started

1. **Clone or Download** the repository to your local machine.
2. Ensure your images directory is set up with the following assets:
images/
├── yeat.jpeg
├── kendrick.jpeg
├── steve.jpeg
├── pinkpanther.jpeg
└── mac.jpeg

3. Open `index.html` in any modern web browser.

---

## 🕹️ Controls

| Input | Action |
| :--- | :--- |
| **Click / Tap** | Expand or collapse an artist's tracklist |
| **`ArrowDown`** | Focus and open the next artist row |
| **`ArrowUp`** | Focus and open the previous artist row |

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
