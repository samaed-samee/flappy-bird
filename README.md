# 🐦 Floppy Bird - Deluxe Edition

A lightweight, modern, and mobile-responsive **Floppy Bird** game built using pure **HTML5 Canvas, Vanilla JavaScript, and CSS3**. Designed with organic flight aerodynamics, multi-tiered feather animations, 5 unique selectable bird skins, and balanced, addictive gameplay.

---

## ✨ Features

- 🎮 **5 Unique Selectable Birds**:
  - 🟡 **Sunny (Classic Gold)**: The iconic, timeless floppy bird.
  - 🔴 **Ruby (Crimson Fire)**: Phoenix-inspired bird with a fiery triple head crest.
  - ⚡ **Volt (Cyber Neon)**: Futuristic electric cyan bird equipped with glowing cyber-visor goggles.
  - 🟢 **Jade (Forest Robin)**: Emerald-hued robin with a sprouting leaf crest.
  - 🟣 **Phantom (Midnight Raven)**: Sleek violet/charcoal raven with glowing mystic eyes and plume feathers.
- 🪶 **Realistic Feather Anatomy & Flying Physics**:
  - **Multi-tiered Wings**: Primary flight feathers with aerodynamic quills + covert shoulder feathers.
  - **Animated Tail Feathers (Retrices)**: Overlapping 3-layer tail feathers that dynamically flutter based on velocity and tilt.
  - **Aerodynamic Pitch & Inertia**: Natural tilt upward (`-24°`) on flaps followed by a smooth nose-down dive curve (`+70°`).
  - **Body Squash & Stretch**: Subtle organic impulse animation on every flap.
- 🎯 **Balanced & Fair Gameplay**:
  - Decoupled forgiving collision hitbox (`11px` inner radius) preventing frustrating pixel clips.
  - Generous pipe gap (`148px`) and relaxed obstacle pacing for rewarding gameplay.
- 📱 **Cross-Platform & Mobile Friendly**:
  - Full touch screen support on mobile devices.
  - Full keyboard (`Space`) and mouse click support on desktop.
- 💾 **Local Persistence**:
  - High score and chosen bird skin persist across sessions via `localStorage`.
- ⚡ **Zero External Dependencies**:
  - Pure HTML5 Canvas, vanilla JavaScript, and separated modular CSS.

---

## 🕹️ Controls

| Action | Desktop | Mobile / Touch |
| :--- | :--- | :--- |
| **Jump / Flap** | `Spacebar` or `Left Mouse Click` | `Tap Screen` |
| **Start / Restart** | `Click Button`, `Click Screen`, or `Spacebar` | `Tap Button` or `Tap Screen` |
| **Select Bird** | `Click Bird Card` | `Tap Bird Card` |

---

## 📁 Project Structure

```bash
floppy-bird-game/
├── floppybird-game.html  # Main game loop, canvas rendering, physics, and skins
├── style.css             # Responsive styling, overlays, and bird picker cards
└── README.md             # Documentation
