# GTA Scroll Animation (Parcel)

Scroll-triggered **Logo Reveal Animation** built with **GSAP + ScrollTrigger** and **Lenis**, bundled using **Parcel**.

## ⚡️ Tech Stack
- [Parcel v2] – Zero-config bundler & dev server  
- [GSAP] + ScrollTrigger – Scroll animations  
- [Lenis] – Smooth scrolling

## ✨ Demo

You can test it Live here :  https://abbas-el-mahmoud.com/scrollanimation/index.html !

## 🚀 Quickstart

**Requirements:** Node.js & npm

```bash
# 1) Clone the repo
git clone https://github.com/AbbasEl11/GTA-Scroll-Animation.git
cd GTA-Scroll-Animation

# 2) Install dependencies
npm install

# 3) Install required packages explicitly (if not already in package.json)
npm install parcel gsap @studio-freight/lenis

# 4) Start the dev server (Parcel)
npm run dev
# or without npm script:
npx parcel index.html --open
```

The dev server will run at `http://localhost:1234/` by default.

## 📦 Production Build

```bash
npm run build
# or:
npx parcel build index.html
```

The optimized build will be in the `dist/` folder (hashed filenames, minified, etc.). You can deploy this folder to any static hosting service.

## 🗂 Project Structure

```
.
├── assets/
│   ├── hero-img-layer-1.png
│   ├── hero-img-layer-2.png
│   └── logo.png
├── index.html
├── style.css
├── script.js
├── logo.js
├── package.json
└── README.md
```

## 🧠 How It Works (Short Version)
1. An **SVG mask overlay** "cuts out" a shape in the overlay, revealing the hero image behind it.  
2. **GSAP + ScrollTrigger** pin the hero section and interpolate scale/opacity during scrolling.  
3. **Lenis** ensures smooth scrolling and keeps ScrollTrigger in sync.

## 🙌 Credits
- Idea/Original: Tutorial by **CodeGrid** (re-implemented for learning purposes)  
- GSAP © GreenSock – Dual license  
- Lenis © Studio Freight – MIT


## 🌐 GitHub Pages (Optional)
- Run `npm run build`
- Push the content of `dist/` to a hosting branch (e.g., `gh-pages`) and enable **Pages** in the repository settings.


Happy coding – and big thanks again to **CodeGrid** for the inspiration! ✌️


## Author
Developed by [AbbasEl11](https://https://github.com/AbbasEl11)

