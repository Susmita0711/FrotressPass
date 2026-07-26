# FortressPass 🛡️
> Fortress-Grade Password Security Telemetry & Generator

A modern, client-side security application designed to analyze password entropy, estimate brute-force crack resilience across multiple attack vectors, and generate high-entropy credentials—100% inside your browser.

---

## 🚀 Live Demo

🔗 https://susmitapasstrenghtchecker.netlify.app/

---

## 📸 Interface Screenshots

<img width="1846" height="906" alt="image" src="https://github.com/user-attachments/assets/45e88210-abfc-49f2-b8cf-56e4f1a1ff73" />
<img width="1810" height="852" alt="image" src="https://github.com/user-attachments/assets/ac3457b0-55b1-4c30-b03c-f01dcbe3268b" />

---

## ✨ Key Features

* **🧠 Shannon Entropy Engine:** Calculates exact information density ($E = L \log_2 R$) while adjusting for sequential character patterns, dictionary matches, and repetition penalties.
* **⚡ Brute-Force Simulation:** Simulates crack resilience against 4 real-world attack vectors, ranging from online rate-limited logins to high-performance GPU supercomputer clusters.
* **🔒 Zero-Server Guarantee:** 100% of calculations and credential generation execute locally using the native `WebCrypto API`. Credentials never touch a network socket or external server.
* **🎲 High-Entropy Generator:** Generate cryptographically secure passwords with custom length and character set preferences.
* **📜 Local History & Utilities:** Track previous password evaluations securely in local browser storage.
* **📱 Offline-Ready / PWA:** Fully operational offline as a Progressive Web App.

---

## 🔐 Security Standards & Alignment

* **NIST SP 800-63B Aligned:** Incorporates modern password composition and entropy guidelines.
* **WebCrypto API Randomness:** Utilizes `crypto.getRandomValues()` instead of `Math.random()` to ensure true cryptographic entropy.
* **100% In-Browser Execution:** Zero telemetry tracking, zero third-party scripts, zero server calls.

---


### Build Settings
* **Build Command:** `npm run build`
* **Publish Directory:** `dist` (or `.next` / `out` depending on framework)

---
