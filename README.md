# 💣 Minesweeper

> **Think. Flag. Survive.** — A classic Minesweeper game with Kids & Adult modes, built as a single zero-dependency HTML file.

[![Play Now](https://img.shields.io/badge/▶_Play_Now-brightgreen?style=for-the-badge)](https://bodhiprotocol.github.io/minesweeper/)
[![View Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github)](https://github.com/BodhiProtocol/minesweeper)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 🎮 Game Modes

| Mode | Grid | Mines | Cell Size | Audience |
|------|------|-------|-----------|----------|
| 🧒 Kids | 8 × 8 | 8 | Large (44px) | Ages 6–10 |
| 🧠 Adult | 16 × 16 | 40 | Classic (28px) | All ages |

## ✨ Features

- **First click always safe** — mines generate after your first click, guaranteed safe zone
- **Flood fill** — clicking an empty cell opens the whole connected region instantly
- **Right-click / long-press** to place or remove flags 🚩
- **Live timer & mine counter** in the HUD
- **Smiley button** resets the board at any time (😊 → 😎 win / 😵 loss)
- **Dark mode** — respects system preference automatically
- **Mobile-friendly** — long-press to flag on touch screens
- Zero dependencies · Works offline · Single HTML file

## 🚀 Play

Open directly in any browser — no server needed:

```
index.html
```

Or play online: **[bodhiprotocol.github.io/minesweeper](https://bodhiprotocol.github.io/minesweeper/)**

## 🛠 How to Run Locally

```bash
git clone https://github.com/BodhiProtocol/minesweeper.git
cd minesweeper
# Open index.html in your browser — that's it
```

## 📁 Project Structure

```
minesweeper/
├── index.html          # The entire game (HTML + CSS + JS)
├── assets/
│   └── preview.svg     # Social preview image (1200×630)
└── .github/
    ├── PULL_REQUEST_TEMPLATE.md
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        └── feature_request.md
```

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

Built with ❤️ by [BodhiProtocol](https://github.com/BodhiProtocol) · Powered by Claude AI
