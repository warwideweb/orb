# ORB — AI-Powered Universal App Interface

A futuristic, installable PWA that replaces traditional app launchers with a single glowing orb.

## ✨ Features

- **Tap** → Radial app menu with smart ranking (most-used apps float to top)
- **Hold** → Voice AI assistant with Gemini-style waveform visualization
- **Real voice recognition** using Web Speech API
- **Haptic feedback** for tactile responses
- **Time-based theming** (morning warm, afternoon blue, night deep)
- **Installable PWA** with offline support

## 🎯 Interactions

| Action | Result |
|--------|--------|
| Single tap | Open radial app menu |
| Long press (500ms) | Activate voice assistant |
| Tap app icon | Launch app (simulated) |
| Voice: "open [app]" | Launch app by voice |
| Voice: "what time" | Get current time |
| Tap outside menu | Close menu |

## 🛠 Tech Stack

- Pure HTML/CSS/JS (no frameworks)
- Web Speech API for voice recognition
- Speech Synthesis for voice responses
- Canvas for particle/waveform animations
- Vibration API for haptics
- Service Worker for offline caching

## 📱 Install

1. Open the live demo on your phone
2. Tap "Install App" when prompted
3. Or use browser menu → "Add to Home Screen"

## 🎨 Design

- **2030 aesthetic** — futuristic, not current Material Design
- **Living entity** — the orb breathes, reacts, glows
- **95% orb** — minimal UI, maximum presence
- **60fps** — butter-smooth animations

## 📁 Structure

```
orb-project/
├── index.html      # Main app
├── manifest.json   # PWA manifest
├── sw.js           # Service worker
├── icons/
│   ├── orb-192.png
│   └── orb-512.png
└── README.md
```

## 🚀 Deploy

Works on any static host: GitHub Pages, Netlify, Vercel, etc.

---

Built with ✨ by War
