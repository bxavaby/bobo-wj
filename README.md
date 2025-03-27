# BOBO, The Web Jester

![LLM-powered](https://img.shields.io/badge/LLM-powered-orange?style=flat-square)
![UI: Cyberpunk Retro](https://img.shields.io/badge/UI-Cyberpunk%20Retro-ff00ff?style=flat-square)
![Frontend](https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-blue?style=flat-square)
![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-green?style=flat-square)
[![MIT License](https://img.shields.io/badge/License-MIT-purple?style=flat-square)](LICENSE)

**Bobo** is a neon-lit joke generator built entirely with the front-end triad and python.  
It runs frontend-only, for now (check out [⧾ Technical Notes](#⧾-technical-notes)), gently falling back to a humorous note when the backend is offline.

---

## ⧾ Demo

⤷ [**Launch Bobo on GitHub Pages**](https://bxavaby.github.io/bobo-wj/)

---

## ⧾ Features

- Pure **frontend** — no dependencies, no build system
- Humor **mode selector** — Clean, Dark, Roast, Geokes (Geography Jokes)
- 🪩 Automatic **fallback**:  
  _"Let's pretend I just said something hilarious *winks.*"_
- Retro-futuristic UI with **glitch effects** and a cursor trail
- Ready for backend plug-in via Flask + Ollama (optional)

---

## ⧾ Technical Notes

- The current version is **frontend-only** and uses a Python backend powered by a locally hosted **fine-tuned LLM**
- Backend connectivity was removed for GitHub Pages hosting
- You can reintroduce backend support by:
  - Modifying the `fetch` logic in `tool.html`
  - Running a lightweight Python script to:
    - Deploy a Flask app that communicates with the frontend
    - Handle the joke generation logic via your preferred LLM (HuggingFace, Ollama, i.a.)

---

## ⧾ Files

- `index.html` – home page, info, links
- `tool.html` – the Web Jester interface
- `style.css` – home page styling
- `tool.css` – WJ styling
- `wape.jpg` – background image

---

## ⧾ Future Ideas

- AI model switcher (local/cloud)
- Save/share jokes
- Voice generation (text-to-speech)
- Bobo, the Pocket Jester

---

## ⧾ License

Licensed under the [MIT License](LICENSE).

---

> ⦿ *Built with love by [@bxavaby](https://github.com/bxavaby) and friends.*
