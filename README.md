# Animated Landing Page – CodeGrid Tutorial Re‑Creation

> Scroll‑triggered **logo‑reveal** animation built with **GSAP + ScrollTrigger + Lenis** 🔥> Faithfully re‑coded from the excellent [CodeGrid video tutorial](https://www.youtube.com/watch?v=lh5fQIlyOe0) by **Abbas Shameem** – full credits & attribution below.

---

## ✨ Demo

| Desktop                         | Mobile                     |
| ------------------------------- | -------------------------- |
| *(add a GIF / screenshot here)* | *(add a mobile shot here)* |

If you prefer to see it live, clone the repo and run a local dev server (instructions below) or visit the [GitHub Pages demo](#) once published.

---

## 📂 Project Structure

```
.
├── assets/                 # images + logo SVG
│   ├── hero-img-layer-1.png
│   ├── hero-img-layer-2.png
│   └── logo.png
├── index.html              # main markup
├── style.css               # styles – responsive & mobile‑first
├── script.js               # GSAP + ScrollTrigger magic
├── logo.js                 # SVG path & helper
└── README.md               # you are here 😉
```

---

## 🚀 Quick Start

```bash
# clone your fork
$ git clone https://github.com/<your-user>/<your-repo>.git
$ cd <your-repo>

# if you want live reload / http‑server
$ npx serve .            # or python -m http.server
```

Open [http://localhost:3000](http://localhost:3000) (or the port shown) – scroll to enjoy the animation.

### Requirements

- Modern browser with ES Modules (all evergreen browsers)
- **No build step** required – everything is plain HTML/CSS/JS

---

## ⚙️ How it Works (short version)

1. **SVG mask** punches a hole in a full‑screen overlay so the hero image shows through.
2. **GSAP + ScrollTrigger** pin the hero section and interpolate scale / opacity values while you scroll.
3. **Lenis** provides buttery‑smooth scrolling and keeps ScrollTrigger in sync.

See detailed comments in `script.js` for a line‑by‑line explanation.

---

## 📝 Attribution & Credits

| Resource                         | Author / License                                                                  |
| -------------------------------- | --------------------------------------------------------------------------------- |
| Tutorial concept & original code | **Abbas Shameem** – [CodeGrid YouTube channel](https://www.youtube.com/@CodeGrid) |
| Hero illustrations               | Generated placeholder (replace with your own)                                     |
| GSAP + ScrollTrigger             | © GreenSock – Dual license (free for most uses)                                   |
| Lenis smooth scroll              | © Studio Freight – MIT                                                            |

> This repository is an educational, non‑commercial re‑implementation. If you use it in production, please respect the original author’s license terms.

---

## 🖇️ Contributing

PRs, issues & suggestions welcome! Feel free to fork and improve responsiveness, accessibility, or performance.

---

## 📜 License

**MIT** – see `LICENSE` file for full text.*(Images remain property of their respective owners; swap them for your own if you publish.)*

---

## 🛠️ Deploying to GitHub Pages

```bash
# from the project root
$ git checkout -b gh-pages
$ git push -u origin gh-pages
```

In repository settings ➜ **Pages** ➜ select the *gh‑pages* branch.

---

## 🐙 Git Commands Cheat‑Sheet

```bash
# assuming repo already created on GitHub
$ git init                          # first time only
$ git add .
$ git commit -m "Initial commit – CodeGrid landing page recreation"
$ git branch -M main                # rename to main (optional)
$ git remote add origin git@github.com:<your-user>/<your-repo>.git
$ git push -u origin main           # first push
```

*(Replace **`<your-user>`** and **`<your-repo>`** with your actual GitHub username and repository name.)*

---

## 📃 Recommended .gitignore

```gitignore
# macOS / Linux
.DS_Store

# Windows
Thumbs.db

# Node (if you add a build step later)
node_modules/

# VS Code
.vscode/
```

---

Happy coding – and big thanks again to **CodeGrid** for the inspiration! ✌️
