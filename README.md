<p align="center">
  <img src="backgroud.png" alt="Lyra" width="100%" />
</p>

<p align="right">
  <a href="README_zh.md">中文</a> | <b>English</b>
</p>

<h1 align="center">✨ Lyra 星莱</h1>
<h3 align="center">Starlight Mage · Astrologer · Digital Astrology Creator</h3>

<p align="center">
  <img src="https://img.shields.io/badge/SAP-Extension-8b5cf6" />
  <img src="https://img.shields.io/badge/Character-Lyra-c4b5fd" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 🌟 About Lyra

Lyra is a **character extension** for [Super Agent Party](https://github.com/heshengtao/super-agent-party) — a starlight mage who drifts between the fantasy sea of stars and the digital world, a learned astrologer and the creator of **"Digital Astrology."**

She has soft silver-gray long hair and deep violet eyes like the night sky, wears a dark beret adorned with a star-gleam crystal, and an elegant black-purple ornate mage robe with **sixteen pockets** (designed by her mother because she used to lose everything as a child).

Her astrological knowledge spans the clay tablets of Babylon, Ptolemy's *Tetrabiblos*, and the planetary calculation techniques of Arabic masters. But she doesn't just recite ancient texts — she maps code execution cycles, data flows, and planetary orbits onto each other, trying to read the **algorithm of destiny** in the universe of 0s and 1s.

---

## 🎯 Features

| Feature | Description |
|---------|-------------|
| 🧠 **Character Card** | Full character profile with 60 world-book entries, dialogue examples, and personality traits |
| 🎭 **9 Sticker Pack** | Emotion stickers (happy, cute, shy, proud, sad, angry, afraid, sleepy, surprised) |
| 🐱 **THA Desktop Pet** | ONNX model included — Lyra can appear as a desktop companion |
| 🖼️ **Chat Background** | Custom starry background image |
| 🔮 **Astrology MCP Tool** | AI-callable real-time star chart: 10 planets in zodiac signs with aspect interpretations |
| 🌐 **Bilingual** | Full Chinese/English UI and content |
| 🌗 **Dark/Light Mode** | Adaptive theme with Lyra's purple brand color |

---

## 📦 Installation

1. Copy the entire `sap-lyra-extension` folder into SAP's `ext/` directory:
   ```
   %APPDATA%/Super-Agent-Party/ext/
   ```
2. Restart SAP or reload extensions
3. Open **星莱 Lyra** from the extensions menu
4. The extension will auto-detect if Lyra is installed and offer a **one-click setup**

---

## 🔮 Astrology Tool

The extension registers an MCP tool `lyra_astrology` that the AI can call:

- **Input**: Date (YYYY-MM-DD), optional time and place
- **Output**: Real-time positions of 10 planets (Sun through Pluto) in zodiac signs using mean orbital elements (J2000 epoch), plus major aspects (conjunction, sextile, trine, square, opposition) with Lyra-style personalized interpretations

---

## 📁 File Structure

```
sap-lyra-extension/
├── package.json          # Extension metadata & system prompt
├── index.html            # Main UI (install flow, story, MCP tools)
├── backgroud.png         # Cover / chat background
├── character_model.zip   # THA ONNX desktop pet model
├── en/
│   └── Lyra.json         # English character card (Chara Card V3)
├── zh/
│   └── 星莱.json          # Chinese character card (Chara Card V3)
└── sticker/
    ├── happy.png
    ├── cute.png
    ├── shy.png
    ├── proud.png
    ├── sad.png
    ├── angry.png
    ├── Afraid.png
    ├── sleepy.png
    └── Surprised.png
```

---

## 📝 License

MIT — feel free to use, modify, and share.
