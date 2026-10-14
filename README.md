# 🍅 FocusSpace — Pomodoro & Ambient Sounds

[![Live Demo](https://img.shields.io/badge/Demo-Live%20App-brightgreen?style=for-the-badge&logo=netlify)](https://focus-space-podomoro.netlify.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A modern, web-based productivity workspace combining a customizable Pomodoro timer, real-time synthesized ambient sounds (powered by the Web Audio API), embedded YouTube music player, and task management with daily streak tracking.

🌐 **Live Demo:** [https://focus-space-podomoro.netlify.app/](https://focus-space-podomoro.netlify.app/)

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Keyboard Shortcuts](#-keyboard-shortcuts)
- [How It Works](#-how-it-works)
- [Tech Stack](#-tech-stack)
- [Privacy & Security](#-privacy--security)
- [Getting Started Locally](#-getting-started-locally)

---

## 📖 Overview

Staying focused in a noisy or distracting environment can be challenging. **FocusSpace** provides an all-in-one distraction-free workspace that pairs structured time-boxing (Pomodoro Technique) with real-time audio soundscapes and task tracking. 

Unlike traditional noise apps, **FocusSpace** synthesizes ambient audio (rain, waves, brown noise) locally in real time using the browser's Web Audio API—eliminating the need to stream or download heavy audio files.

---

## 📸 Preview

<img width="1909" height="905" alt="image" src="https://github.com/user-attachments/assets/8064320c-b0ec-466f-9d3d-186258f8d145" />

---

## 🌟 Key Features

- **🎯 Customizable Pomodoro Timer:** Seamless switching between Focus, Short Break, and Long Break modes with auto-cycling options.
- **🌧️ Real-Time Synthesized Ambient Sounds:** Generates high-quality ambient audio (Rain, Ocean Waves, Cafe ambiance, Deep Brown Noise) on-the-fly using the Web Audio API without fetching external sound files.
- **🎵 Integrated YouTube Music Player:** Play embedded background music or select pre-curated chill playlists (Lofi Radio, Chillhop, Chill Jazz).
- **📝 Task & Active Task Tracker:** Add tasks, set estimated Pomodoro intervals, and attach active tasks directly to your timer.
- **🔥 Daily Stats & Streak Counter:** Track completed Pomodoro sessions and build consistent daily productivity habits.
- **🧘 Zen / Focus Mode:** Hide all interface clutter with a single click or keyboard shortcut (`F`) for full immersion.
- **🔒 Privacy-First Architecture:** 100% client-side application. All tasks, settings, and history stay safely on your device in `localStorage`.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Space</kbd> | Start / Pause Timer |
| <kbd>F</kbd> | Toggle Zen / Focus Mode |
| <kbd>Esc</kbd> | Exit Zen Mode / Close Modals & Dialogs |

---

## 🔄 How It Works

1. **Set Up Your Task:** Add a task to the checklist and assign an estimated number of Pomodoros.
2. **Choose Your Soundscape:** Mix real-time synthesized ambient sounds or load your favorite YouTube focus playlist.
3. **Start the Timer:** Press `Space` to initiate your focus session.
4. **Enter Zen Mode:** Press `F` to clear away UI distractions.
5. **Take Breaks & Track Progress:** Follow the automated break cycles and build your daily focus streak!

---

## 🛠️ Tech Stack

- **UI & Styling:** HTML5, Tailwind CSS, Lucide Icons
- **Application Logic:** Vanilla JavaScript (ES6+)
- **Audio Engine:** Web Audio API (Synthesized background audio & chime notifications)
- **Integrations:** YouTube IFrame Player API
- **Storage:** Web Storage API (`localStorage`)
- **Hosting:** [Netlify](https://www.netlify.com/)

---

## 🔒 Privacy & Security

- **Zero Data Collection:** Your tasks, timers, and productivity stats are never uploaded to any backend server.
- **No Heavy Downloads:** Ambient audio sounds are generated algorithmically inside your browser, saving bandwidth and keeping performance ultra-lightweight.

---

## 🚀 Getting Started Locally

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/karinaara/focus-space.git](https://github.com/karinaara/focus-space.git)
cd focus-space
