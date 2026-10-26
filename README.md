# 🐦 Floppy Bird - Deluxe Edition

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Play%20Now-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://samaed-samee.github.io/flappy-bird/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/samaed-samee/flappy-bird)
[![Developer](https://img.shields.io/badge/Developer-Samee-orange?style=for-the-badge&logo=github)](https://github.com/samaed-samee/)

A modern, responsive **Floppy Bird** game built with pure **HTML5 Canvas, Vanilla JavaScript, and CSS3**. Features organic aerodynamic flight physics, multi-tiered animated feathers, 5 unique selectable bird characters, and balanced, rewarding gameplay.

🎮 **[Play the Live Game Here!](https://samaed-samee.github.io/flappy-bird/)**

---

## 👨‍💻 Developer Information

- **Developer:** [Samee](https://github.com/samaed-samee/)
- **GitHub Profile:** [https://github.com/samaed-samee/](https://github.com/samaed-samee/)
- **Repository:** [https://github.com/samaed-samee/flappy-bird.git](https://github.com/samaed-samee/flappy-bird.git)
- **Live Website:** [https://samaed-samee.github.io/flappy-bird/](https://samaed-samee.github.io/flappy-bird/)

---

## ✨ Features

### 1. 🪶 5 Selectable Bird Characters
Choose between 5 birds with distinct palettes, anatomy, and head ornaments:
- 🟡 **Sunny (Classic Gold)**: The beloved, iconic yellow floppy bird.
- 🔴 **Ruby (Crimson Fire)**: Phoenix-inspired bird with a fiery triple head crest.
- ⚡ **Volt (Cyber Neon)**: Electric cyan cyber bird equipped with glowing futuristic visor goggles.
- 🟢 **Jade (Forest Robin)**: Emerald-green robin sporting a cute sprout leaf crest.
- 🟣 **Phantom (Midnight Raven)**: Mystical charcoal/violet raven with glowing golden eyes and plume feathers.

### 2. 🦅 Realistic Flight Physics & Aerodynamics
- **Multi-tiered Wings**: Primary flight feathers with aerodynamic quill shafts and scalloped shoulder coverts.
- **Animated Tail Feathers (Retrices)**: 3-layer overlapping tail feathers that flutter dynamically with flight angle and velocity.
- **Natural Pitch Inertia**: Smooth upward lift tilt (`-24°`) transitioning into an organic nose-down dive curve (`+70°`).
- **Squash & Stretch**: Dynamic body deformation on each flap impulse.
- **Fair Hitbox**: Generous `11px` inner collision core so grazing pipe edges doesn't cause cheap deaths.

### 3. 📱 Mobile-Friendly & Cross-Platform
- Fully responsive on mobile phones, tablets, and desktop displays.
- Supports both full-screen touch gestures and keyboard/mouse clicks.

### 4. 💾 Persistent High Scores & Selection
- Saves your high score and selected bird character locally using `localStorage`.

---

## 🕹️ How to Play

| Action | Desktop Controls | Mobile / Touch Controls |
| :--- | :--- | :--- |
| **Jump / Flap** | `Spacebar` or `Click Screen` | `Tap Screen` |
| **Start / Replay** | `Click Button` or `Spacebar` | `Tap Button` or `Tap Screen` |
| **Select Bird** | `Click Bird Card` | `Tap Bird Card` |

---

## 📁 Project Structure

```bash
flappy-bird/
├── index.html            # Main game entry point (GitHub Pages)
├── floppybird-game.html  # Standalone game file
├── style.css             # Glassmorphism UI, overlay states, and animations
└── README.md             # Project documentation
```

---

## 🚀 Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/samaed-samee/flappy-bird.git
   ```
2. Navigate into the folder:
   ```bash
   cd flappy-bird
   ```
3. Open `index.html` or `floppybird-game.html` in any web browser.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

Developed with ❤️ by **[Samee](https://github.com/samaed-samee/)**.
