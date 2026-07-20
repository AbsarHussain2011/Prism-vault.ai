# ✈️ Prism Vault AI — Departures

A curated, airport-departures-board-styled directory of **500+ AI tools and assistants** — spanning chat, coding, image/video/music generation, productivity, business operations, and specialized industries. Built as a single self-contained HTML file with no build step and no dependencies beyond Google Fonts.

![Made with HTML/CSS/JS](https://img.shields.io/badge/built%20with-HTML%2FCSS%2FJS-orange)
![No dependencies](https://img.shields.io/badge/dependencies-none-blue)
![License: MIT](https://img.shields.io/badge/license-MIT-green)

---

## ✨ Features

- 🛫 **Departure-board aesthetic** — split-flap load animations, terminal tabs, and gate-style listings
- 🔍 **Instant search** across all 500 assistants by name, purpose, or category
- 🌗 **Light / dark theme toggle** with smooth transitions
- 🗂️ **28 categories across 6 terminals**:
  - Chat & Research
  - Coding & Dev
  - Creative Media (image, video, music & voice)
  - Design & Productivity
  - Business & Ops
  - Specialized (education, healthcare, 3D/gaming, translation, avatars, browsing agents)
- 📡 **Live ticker marquee** showing tool count and highlights
- 📱 **Fully responsive** — clean layout on mobile and desktop
- ⬇️ **One-click download** of the page as a standalone HTML file
- ⌨️ **Keyboard shortcuts** — press `/` to focus search, `Esc` to clear
- ♿ Accessible markup with ARIA labels and `prefers-reduced-motion` support

---

## 🖥️ Tech Stack

Pure **HTML, CSS, and vanilla JavaScript** — no frameworks, no bundlers, no npm install. Just open the file in a browser.

---

## 🚀 Usage

Clone the repo and open the file directly in your browser:

```bash
git clone https://github.com/<your-username>/prism-vault-ai.git
cd prism-vault-ai
open index.html
```

Or serve it locally with any static file server:

```bash
python3 -m http.server
# then visit http://localhost:8000
```

---

## 📁 Project Structure

```
prism-vault-ai/
├── index.html      # entire app — markup, styles, data, and logic in one file
└── README.md
```

All tool data lives in a single `TERMINALS` array near the top of the `<script>` block, making it easy to add, edit, or remove entries.

## 🧩 Adding a New Tool

Find the relevant category inside the `TERMINALS` array and add an entry in this format:

```js
["Tool Name", "https://tool-url.com", "Short one-line description", true /* optional: adds an "open" icon */]
```

Categories are grouped under terminals (pages), each with a unique single/double-letter code used for gate numbers (e.g. `A1`, `C12`).

---

## 🤝 Contributing

Found a great AI tool that's missing, or spotted an outdated link? Contributions are welcome:

1. Fork the repo
2. Add/update entries in the `TERMINALS` array
3. Open a pull request

You can also suggest a tool directly via the contact link on the page.

---

## 📄 License

Released under the [MIT License](LICENSE).

---

Created by **Absar Hussain Shaikh**
