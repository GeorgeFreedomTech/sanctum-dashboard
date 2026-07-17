# The Sanctum Dashboard

A minimalist, simple tracking dashboard designed as a personal media log for **George Freedom**. 

Built with an intentional "wizard’s study / arcane knowledge" aesthetic — obsidian dark and glowing candle-flame accents. Zero-backend architecture with client-side Markdown execution, zero tracking, and absolute data ownership. Maps three categories (Books, Movies, Games) split into **Chronicle** (finished) and **Quest** (to watch/read/play list).

## Tech Stack

- **HTML5** (Semantic layout and single-page container structure)
- **Pico CSS** (Minimalist, lightweight classless CSS framework)
- **Custom CSS** (Arcane design system, Google Fonts integration for Cinzel/Lora, and typography fallback locks)
- **Marked.js** (Lightweight, client-side asynchronous Markdown compilation)
- **GitHub Pages** (Production hosting and deployment via global CDN)

## Key Features

* **Arcane Aesthetics:** Dark theme layout featuring a clean typography hierarchy (Cinzel for headers, Lora for body text) tailored to fit the "wizard's study" concept.
* **Dual-Ledger Navigation:** Fast switching between **Chronicle** (favorites) and **Quest** (backlog) lists without page reloads.
* **Client-Side Architecture:** Zero database setup. Flat Markdown files are fetched asynchronously and rendered on the fly using vanilla JS and `marked.js`.
* **Zero Bloat:** No servers, no tracking scripts, and no cookies. A lightweight single-page system built for local execution and complete data ownership.

## Architecture

This repository uses a streamlined, flat layout to handle asset delivery and Markdown files from a single root directory.

```text
├── index.html          # Main Sanctum entry point (SPA)
│
├── content/            # Flat file repository for all tracking nodes
│   ├── favorites/      # The Chronicle ledger (Verified logs)
│   │   ├── books.md
│   │   ├── movies.md
│   │   └── games.md
│   └── backlog/        # The Quest ledger (Backlog logs)
│       ├── books.md
│       ├── movies.md
│       └── games.md
│
├── static/             # Unified production assets
│   ├── css/
│   │   ├── custom.css  # Core design system & amber glow aesthetics
│   │   └── pico.min.css
│   └── js/
│       └── marked.min.js
│
├── LICENSE.md          # License documentation
└── README.md           # System documentation
```


## 🔗 Let's Connect:

* Visit my website: **[https://GeorgeFreedom.com](https://GeorgeFreedom.com)**
* Connect on LinkedIn: **[https://www.linkedin.com/in/georgefreedom/](https://www.linkedin.com/in/georgefreedom/)**
* Let's talk: **[https://cal.com/georgefreedom](https://cal.com/georgefreedom)**


## 📜 License:

Copyright (c) 2026 Jiří Svoboda (George Freedom) / George Freedom Tech

This project is licensed under:
* Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

---

We build for the Future!
