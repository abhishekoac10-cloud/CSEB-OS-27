# 🎯 CSEB Web OS 27 | 

![Version](https://img.shields.io/badge/Version-3.1_Beta-blue?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Tech-Pure_HTML/CSS/JS-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active_Development-success?style=for-the-badge)

A high-performance, glassmorphism-inspired web operating system designed exclusively for Kerala CSEB (Co-operative Service Examination Board) Junior Clerk aspirants. 

More than just a dashboard, this is a centralized **Adaptive Learning Platform** that tracks study velocity, syncs data across tabs in real-time, and generates neural insights to optimize exam preparation.

---

## ✨ Key Features

### 🧠 Adaptive Neural Engine v2
Analyzes daily study progress against the elapsed timeline to calculate an **Exam Readiness Score (ERS)**. It actively identifies your weakest subjects (e.g., Co-op Law, Reasoning) and generates dynamic text insights instructing you on what to prioritize to stay on track.

### ⚡ Real-Time Active Sync (Cross-Tab)
Powered by `localStorage` event listeners, the OS seamlessly synchronizes your study stats, notifications, and login state across multiple open tabs. If you log out in one window, the **Global Logout System** instantly locks down the entire ecosystem.

### 🎨 OS-Level Glassmorphism UI
Built with a premium Apple-inspired design system featuring:
- Heavy `saturate(160%)` frosted glass panels.
- Ambient, performance-optimized floating parallax orbs.
- Haptic-style CSS hover physics and scale animations.
- **AMOLED Dark Mode** toggle for late-night study sessions.
- **Zen Mode** to blur out distractions and enforce deep-work focus.

### ⏱️ Precision Exam Countdown & Timeline
A live, tick-by-tick countdown to Exam Day paired with a visual **Phase Timeline** that automatically shifts your OS state from *Preparation* ➡️ *Revision* ➡️ *Exam Day*.

### 🔔 Smart Notification Center
An intelligent notification tray that generates automated study nudges based on the time of day, streak warnings, and milestone celebrations.

---

## 🛠️ Tech Stack

This project is built **100% without frameworks or external libraries**. 
* **HTML5:** Semantic, accessible structure.
* **CSS3:** Custom variables, advanced Grid/Flexbox layouts, backdrop-filters, and hardware-accelerated animations (`transform`, `opacity`).
* **Vanilla JavaScript (ES6+):** * Custom `requestAnimationFrame` wrappers (`Perf.scheduleDOMWrite`) to prevent layout thrashing.
  * LocalStorage-based pseudo-database for session tracking and progress saving.
  * Intersection Observers for scroll-reveal animations.

---

## 🚀 Getting Started

Since this is a pure Vanilla frontend application, no build steps, NPM installs, or servers are required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/abhishekoac10-cloud/CSEB-OS-27.git](https://github.com/abhishekoac10-cloud/CSEB-OS-27.git)
