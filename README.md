# 🎵 Chromatic Tuner PWA

A sleek, highly accurate, browser-based chromatic instrument tuner. Built with vanilla web technologies, this tuner features a modern glassmorphism UI, real-time pitch detection, and dual notation support for both Western and Indian (Hindustani) musical scales.

## ✨ Features

* **Dual Scale Display:** Instantly translates pitches into Western notation (e.g., C#, D with subscript octaves) and exact Indian Sargam notations (Devanagari script with diacritics + Roman script).
* **High-Precision Audio:** Utilizes the Web Audio API and an advanced Autocorrelation algorithm to detect pitch frequencies with extreme accuracy.
* **Liquid Bubble Meter:** A unique, fluid "spirit-level" accuracy meter gives you granular, real-time visual feedback on whether you are sharp, flat, or perfectly in tune (+/- 50 cents).
* **Glassmorphism UI:** A modern, dark-themed, translucent interface with fixed positioning to ensure zero layout shifts while tuning. 
* **Progressive Web App (PWA):** Fully installable on iOS, Android, and Desktop. Includes a Service Worker for 100% offline functionality after the first load.
* **Privacy First:** All audio processing is done locally on your device. No audio data is ever recorded or transmitted.
