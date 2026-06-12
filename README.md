# 🎙️ AuraVoice AI

https://somdeepkundu.github.io/ai-voice-reader/
An elegant, offline-first, client-side AI Text-to-Speech (TTS) application designed to run completely inside your web browser. Built using **React**, **Tailwind CSS**, and modern web standards, AuraVoice AI allows you to convert text manuscripts and research papers into natural speech with zero server overhead and absolute privacy.

---

## ✨ Features

* **🔒 100% Client-Side Privacy**: All speech synthesis processing is executed locally within your browser using WebAssembly. Your text documents and audio files never touch an external server.
* **🌐 GitHub Pages Ready**: Zero build steps or server-side requirements. Drop the `index.html` file straight into a repository, activate GitHub Pages, and your application is instantly live.
* **🎯 Scientific & Academic Focus**: Optimized for reading long-form text passages, academic papers, or daily manuscripts hands-free.
* **⚡ Responsive & Modern UI**: Built with a sleek, dark-themed control center powered by Tailwind CSS, perfectly optimized for both desktop and mobile layouts.
* **🏃 Dynamic Playback Control**: Adjust speech pacing seamlessly from `0.5x` up to `2.0x` speed to match your listening preference.

---

## 🚀 Quick Start & Deployment

Deploy your own instance of AuraVoice AI to GitHub Pages in under two minutes:

1. **Create a GitHub Repository**: Name it something descriptive (e.g., `ai-voice-reader`).
2. **Add the Application File**: Commit your `index.html` file directly to the root of your `main` branch.
3. **Enable GitHub Pages**:
   * Navigate to the **Settings** tab of your repository.
   * Click **Pages** in the left sidebar under the "Code and automation" section.
   * Under **Build and deployment**, set the source to **Deploy from a branch**.
   * Select your `main` branch and `/ (root)` folder, then hit **Save**.
4. **Launch**: Your personal AI reader will be live shortly at `https://<your-github-username>.github.io/ai-voice-reader/`.

---

## 🛠️ Architecture & Core Dependencies

AuraVoice AI leverages lightweight CDN-delivered micro-dependencies to bypass complex local compilation pipelines and toolchains:

* **UI Framework**: [React 18](https://react.dev/) (Production CDN bundle)
* **Styling Engine**: [Tailwind CSS v4](https://tailwindcss.com/) (Just-In-Time runtime script)
* **Compiler Standalone**: [Babel Standalone](https://babeljs.io/) (On-the-fly JSX transpilation)
* **Core APIs**: Native Browser `WebAssembly` network pipelines and `SpeechSynthesisUtterance` hooks.

---

## 🛡️ License

Distributed under the MIT License. See `LICENSE` for more information.

---

**AuraVoice AI** — *Where your papers find their voice, privately. 🎧*
