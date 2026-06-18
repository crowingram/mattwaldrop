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
│   ├── primary.css     # Site styles — modern CSS (custom properties + native nesting), no build step
│   └── index.html      # Redirect to root for direct /css/ visits
├── media/              # Logo and media assets
├── index.html          # Homepage (Resume)
├── about.html          # Personal bio and mission
├── projects.html       # Portfolio/projects page
├── colophon.html       # Site information
└── README.md           # This file
```

---

### 🎨 Styling

Styling is hand-authored **modern CSS** (`css/primary.css`) using custom properties and native CSS nesting — no Sass/preprocessor and no build step.
Theme tokens (colors, fonts) live in `:root`, so the palette is editable in one place and can be re-themed at runtime.
