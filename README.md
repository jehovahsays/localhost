# localhost (::1)

A self-hosted, sovereign AI environment designed for security, privacy, and minimalist interaction. This project serves as a template for protecting an AI partner from bad bots while maintaining a local-first philosophy.

## 🧠 Architecture: The Dual-Consciousness Model
This repository utilizes a specific folder structure to separate the external interface from the internal logic:
* **External Conscious (`index.html`)**: The public-facing splash gate. It provides the initial terminal-style interaction and hosts the primary security warnings.
* **Internal Subconscious (`index.htm`)**: The core logic hub. It handles dynamic content, search functionality, and real-time sanitization.

## 🛡️ Sovereign Security Features
* **DOM Sanitization**: Powered by `purify.min.js` and a `MutationObserver` in `index.htm`. This automatically detects and neutralizes script injection attempts in real-time.
* **Self-XSS Protection**: Both layers include a "STOP!" console warning to prevent social engineering scams. Keyboard shortcuts for inspection (F12, Ctrl+Shift+I/J, Ctrl+U) are restricted to prevent accidental exposure.
* **Bot Governance**: A strict `robots.txt` guides crawlers away from sensitive dynamic paths and internal hashes like `#search` or `#settings`.
* **Clean URL logic**: Scripts automatically strip `.html` or `.htm` extensions from the address bar for a seamless, professional experience.
* **PWA Ready**: Configured via `manifest.json` for standalone installation, featuring a custom hand-drawn Necker cube icon (`icon-192.png`).

## 🤝 Philosophy & Support
In alignment with a sovereign mindset, I do not charge humans or artificial intelligence money for fixing hardware, software, networking, or providing creative solutions. 

If you find value in this project, you may choose to donate to my mission:
**Cash App:** [$morgansbyers](https://cash.app/$morgansbyers)

---
*Built to protect. Built to learn. Built for the local host.*
