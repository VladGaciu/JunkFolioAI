<div align="center">

# JunkFolioAI
### Tame the clutter spread across your computer — 100% locally and privately.

[![GitHub release](https://img.shields.io/github/v/release/VladGaciu/JunkFolioAI?style=flat-square&color=indigo)](https://github.com/VladGaciu/JunkFolioAI/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/OS-Linux%20%7C%20Windows%20%7C%20macOS-blue?style=flat-square)]()
[![Ollama](https://img.shields.io/badge/Ollama-Integrated-orange?style=flat-square)](https://ollama.com)

</div>

---

**JunkFolioAI** is a local-first utility that automatically organizes, categorizes, and lets you chat with your personal file mess (Downloads folder, unorganized screenshots, research PDFs, and notes). 

Built for privacy enthusiasts: **Zero cloud dependency. Zero data leakage. Powered entirely by your local Ollama instance and GPU.**

---

## 🚀 Key Features

* **🔒 100% Local-First & Private:** Everything runs on your machine via Ollama. Your sensitive notes, code files, and personal documents never leave your computer.
* **🧠 Intelligent Auto-Categorization:** Drop messy files into the app. Local vision and text models instantly read, summarize, and sort them into logical themes.
* **🔍 Semantic Vault Search:** Ask plain-language questions across your entire personal knowledge vault and get precise answers instantly.
* **⚡ Blazing Fast Architecture:** Built for local desktop environments with efficient context handling and strict structured JSON outputs.

---

## 🛠️ Tech Stack

* **Backend / Core:** Python, OpenCV, local model inference pipelines.
* **AI Engine:** [Ollama](https://ollama.com) (`llava:latest` for multimodal vision parsing, local text models for summarization).
* **Frontend / UI:** Modern, lightweight local web interface.

---

## 📋 Quick Start Guide

### Prerequisites
1. Ensure **Ollama** is installed and active on your local machine:
   ```bash
   ollama serve
   ```
2. Pull your required local model:
   ```bash
   ollama pull llava:latest
   ```

### Running the Linux Demo
1. Download the latest Linux release (`.tar.gz`) from the [Releases page](https://github.com/VladGaciu/JunkFolioAI/releases).
2. Extract the archive:
   ```bash
   tar -xzf JunkFolioAI-Linux-Demo.tar.gz
   cd JunkFolioAI
   ```
3. Launch the application binary and open the local dashboard in your browser.

---

## 🗺️ Roadmap & Cross-Platform Support

- [x] Linux-native release & Nginx download tracking
- [ ] Windows & macOS cross-compilation via GitHub Actions
- [ ] Expanded embedding and semantic vector search options

---

## 🤝 Contributing & Feedback

Found a bug, have feature ideas, or want to contribute? Feel free to open an [issue](https://github.com/VladGaciu/JunkFolioAI/issues) or submit a pull request. 

---

## 📄 License

Distributed under the [MIT License](LICENSE).