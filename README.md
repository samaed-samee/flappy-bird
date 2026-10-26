# 🐦 Flappy Bird - Deluxe Edition

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Play%20Now-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://samaed-samee.github.io/flappy-bird/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/samaed-samee/flappy-bird)
[![Developer](https://img.shields.io/badge/Developer-Samee-orange?style=for-the-badge&logo=github)](https://github.com/samaed-samee/)
[![P2P Multiplayer](https://img.shields.io/badge/Multiplayer-2P%20Couple%20Mode-ff69b4?style=for-the-badge&logo=webrtc&logoColor=white)](https://samaed-samee.github.io/flappy-bird/)
[![E2EE Voice Chat](https://img.shields.io/badge/Voice%20Chat-End--to--End%20Encrypted-10b981?style=for-the-badge&logo=signal&logoColor=white)](https://samaed-samee.github.io/flappy-bird/)

A modern, responsive **Flappy Bird** game built with pure **HTML5 Canvas, Vanilla JavaScript, CSS3, and PeerJS**. Features **Solo Play** and **2-Player Couple Multiplayer** with a **10-character room code**, **live WebRTC voice chat (mic on/off)**, **End-to-End Encryption (E2EE)**, organic aerodynamic flight physics, multi-tiered animated feathers, and 5 unique selectable bird characters.

🎮 **[Play the Live Game Here!](https://samaed-samee.github.io/flappy-bird/)**

---

## 👨‍💻 Developer Information

- **Developer:** [Samee](https://github.com/samaed-samee/)
- **GitHub Profile:** [https://github.com/samaed-samee/](https://github.com/samaed-samee/)
- **Repository:** [https://github.com/samaed-samee/flappy-bird.git](https://github.com/samaed-samee/flappy-bird.git)
- **Live Website:** [https://samaed-samee.github.io/flappy-bird/](https://samaed-samee.github.io/flappy-bird/)

---

## ✨ Features

### 1. 💑 Real-Time P2P Couple Multiplayer (PeerJS)
- **10-Character Room Code**: Quick, easy room creation (e.g. `K9X2M7P4Q1`) with one-click copy to share with your partner via WhatsApp or chat.
- **Synchronized Gameplay**: Both players fly together in the exact same arena with identical pipes and gaps.
- **Partner Bird Visualization**: View your partner's chosen skin, flight angles, and flapping in real-time, marked with a floating `Partner ❤️` badge.
- **Dual Live Scoreboard**: Displays both players' scores (`YOU: X | PARTNER: Y`) during flight and a head-to-head winner summary on Game Over.

### 2. 🎙️ Live Voice Chat with Mic On/Off
- Direct peer-to-peer WebRTC microphone streaming.
- **Mic Mute / Unmute Button**: Toggle your mic anytime before launching or while flying using the in-game floating mic button.
- Real-time visual mic indicators (Active Green 🎙️ / Muted Red 🔇).

### 3. 🔒 End-to-End Encryption (E2EE)
- Built on direct device-to-device WebRTC technology.
- Audio media streams are protected with **DTLS-SRTP encryption** and game sync data is protected with **SCTP DTLS**. No intermediate voice server listens or records your conversation.

### 4. 🪶 5 Selectable Bird Characters
Choose between 5 birds with distinct palettes, anatomy, and head ornaments:
- 🟡 **Sunny (Classic Gold)**: The beloved, iconic yellow flappy bird.
- 🔴 **Ruby (Crimson Fire)**: Phoenix-inspired bird with a fiery triple head crest.
- ⚡ **Volt (Cyber Neon)**: Electric cyan cyber bird equipped with glowing futuristic visor goggles.
- 🟢 **Jade (Forest Robin)**: Emerald-green robin sporting a cute sprout leaf crest.
- 🟣 **Phantom (Midnight Raven)**: Mystical charcoal/violet raven with glowing golden eyes and plume feathers.

### 5. 🦅 Realistic Flight Physics & Aerodynamics
- **Multi-tiered Wings**: Primary flight feathers with aerodynamic quill shafts and scalloped shoulder coverts.
- **Animated Tail Feathers (Retrices)**: 3-layer overlapping tail feathers that flutter dynamically with flight angle and velocity.
- **Natural Pitch Inertia**: Smooth upward lift tilt (`-24°`) transitioning into an organic nose-down dive curve (`+70°`).
- **Squash & Stretch**: Dynamic body deformation on each flap impulse.
- **Fair Hitbox**: Generous `11px` inner collision core so grazing pipe edges doesn't cause cheap deaths.

### 6. 📱 Mobile-Friendly & Cross-Platform
- Fully responsive on mobile phones, tablets, and desktop displays.
- Supports full-screen touch gestures and keyboard/mouse clicks.
- Saves your high score and bird preference locally via `localStorage`.

---

## 🕹️ How to Play

### Solo Mode:
1. Select your bird skin on the home screen.
2. Click **SOLO PLAY** (or tap screen / press Space).
3. Avoid pipes and score as high as possible!

### Couple Multiplayer Mode (2 Players):
1. Click **COUPLE 2P ❤️**.
2. **Player 1 (Host)**: Click **GENERATE 10-CHAR CODE** and share the 10-character code with Player 2.
3. **Player 2 (Partner)**: Enter the 10-character code into the box and click **JOIN**.
4. Both players' mics connect automatically (toggle mute on/off with 🎙️/🔇).
5. Host clicks **START TOGETHER 🚀** to fly side-by-side!

---

## 🎮 Controls Reference

| Action | Desktop Controls | Mobile / Touch Controls |
| :--- | :--- | :--- |
| **Jump / Flap** | `Spacebar` or `Click Screen` | `Tap Screen` |
| **Toggle Mic (Mute/Unmute)** | `Click 🎙️ / 🔇 Button` | `Tap 🎙️ / 🔇 Button` |
| **Start / Replay** | `Click Button` or `Spacebar` | `Tap Button` or `Tap Screen` |
| **Select Bird** | `Click Bird Card` | `Tap Bird Card` |

---

## 📁 Project Structure

```bash
flappy-bird/
├── index.html   # Main game entry point (P2P multiplayer, voice chat, canvas)
├── style.css    # Glassmorphism UI, multiplayer modal, and animations
└── README.md    # Project documentation
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
3. Open `index.html` in any web browser.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

Developed with ❤️ by **[Samee](https://github.com/samaed-samee/)**.
