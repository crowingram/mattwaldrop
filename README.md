# mattwaldrop

## 🌐 Matthew Waldrop | Personal Website

Welcome to the repository for the personal portfolio and resume site of **Matthew Waldrop**, a seasoned Web Developer with deep experience in HTML, CSS, JavaScript, and PHP.

This site showcases professional experience, technical skills, project references, and work history, all optimized for performance and accessibility.

---

### 🚀 Live Site

[Visit mattwaldrop.com](https://www.mattwaldrop.com)

---

### 📂 Project Structure

```bash
.
├── css/
│   ├── primary.css     # Site styles — modern CSS (custom properties), no build step
│   └── index.html      # Redirect to root for direct /css/ visits
├── media/              # Logo and media assets
├── index.html          # Single-page site — résumé, work, experience, skills, projects, education
├── colophon.html       # How the site is built
├── .htaccess           # HTTPS, security headers, hidden-file blocking, legacy redirects
└── README.md           # This file
```

---

### 🎨 Styling

Styling is hand-authored **modern CSS** (`css/primary.css`) using custom properties (design tokens) — no Sass/preprocessor and no build step.
Theme tokens (colors, fonts) live in `:root`, and every color is drawn from the site's original palette.
