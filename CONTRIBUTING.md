# Contributing Guide

Thank you for your interest in contributing to **GTA Scroll Animation**! ❤️

This project uses **Parcel** as a bundler, **GSAP + ScrollTrigger** for animations, and **Lenis** for smooth scrolling.

## 🛠 How to Contribute

1. **Fork** the repository on GitHub.

2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/GTA-Scroll-Animation.git
   cd GTA-Scroll-Animation
   ```

3. **Install dependencies** (Node.js & npm required):
   ```bash
   npm install
   ```

4. **Create** a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

5. **Make your changes** to the codebase.

6. **Run the development server** to test locally:
   ```bash
   npm run dev
   # or
   npx parcel index.html --open
   ```

7. **Commit** your changes:
   ```bash
   git commit -m "Add your amazing feature"
   ```

8. **Push** your branch:
   ```bash
   git push origin feature/your-feature-name
   ```

9. **Open** a Pull Request describing your changes and the motivation.

---

## 📏 Guidelines

- Follow the existing code style (HTML, CSS, JS formatting).
- Keep PRs focused – one feature or fix per PR.
- Include screenshots or GIFs for any UI changes.
- Update documentation (README, comments) if you change functionality.
- Make sure the build passes without errors:
  ```bash
  npm run build
  ```

---

## 🐛 Reporting Bugs

When opening an issue, please include:

- A clear and descriptive title.
- Steps to reproduce the issue.
- Expected vs actual behavior.
- Screenshots or videos, if helpful.
- Browser & OS information.

---

## 📜 Code of Conduct

Please note we have a [Code of Conduct](CODE_OF_CONDUCT.md).  
By participating, you agree to abide by its terms.

---

**Tip:** If you're adding new dependencies (e.g., GSAP plugins or scroll libraries), ensure they are installed and saved in `package.json`:
```bash
npm install <package-name> --save
```
