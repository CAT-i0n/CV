# Ivan Rudman — CV

A simple, responsive, single-page CV website built with plain **HTML, CSS and JavaScript**.
No build step, no dependencies — ready to publish on **GitHub Pages**.

## ✨ Features

- One-page layout: Hero, Skills, Experience, Education, Contact
- Responsive (desktop / tablet / mobile with burger menu)
- Light & dark theme (auto-detects system preference, remembers your choice)
- Smooth scrolling + scroll-spy navigation
- Reveal-on-scroll animations and animated counters
- Print-friendly (prints a clean, dark-on-white CV)
- Downloadable PDF version of the CV

## 📁 Structure

```
.
├── index.html            # Markup
├── css/style.css         # Styles (design tokens, light/dark themes)
├── js/script.js          # Theme toggle, menu, scroll effects
├── Curriculum_Vitae.pdf  # Downloadable CV
└── README.md
```

## 🚀 Publish on GitHub Pages

1. Push this repository to GitHub:
   ```bash
   git add .
   git commit -m "Add CV website"
   git push origin main
   ```
2. On GitHub go to **Settings → Pages**.
3. Under **Build and deployment → Source** choose **Deploy from a branch**.
4. Select branch **`main`** and folder **`/ (root)`**, then **Save**.
5. The site goes live at:
   - `https://<username>.github.io/` — if the repo is named `<username>.github.io`
   - `https://<username>.github.io/<repo>/` — for any other repo name

## 🛠 Local preview

Just open `index.html` in a browser, or run a tiny server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## ✏️ Customizing

- **Content** — edit `index.html` (name, summary, skills, jobs, education, contacts).
- **Colors / theme** — edit the CSS custom properties at the top of `css/style.css`
  (`--accent`, `--accent-2`, backgrounds, etc.).
- **Share preview URL** — update the `og:url` meta tag in `index.html` to your live URL.
- **New CV file** — replace `Curriculum_Vitae.pdf`, keeping the same file name.

## 📄 License

Content © Ivan Rudman. Code free to reuse.
