# MDK Portfolio

Personal portfolio website of **Muhammad Danyal Khan** — a Software Engineering student at Iqra National University, Peshawar, showcasing skills, education, and projects in Flutter, Python, and C++ development.

**Live site:** _add your deployed URL here (e.g. GitHub Pages / Vercel / Netlify link)_

---

## About

This repository contains the source code for a single-page, responsive portfolio website. It's built with plain HTML, CSS, and JavaScript — no frameworks or build tools required — and is designed to present:

- A brief professional background and academic stats
- Technical skills with visual proficiency indicators
- Educational timeline
- A filterable showcase of projects
- Services offered
- FAQs and testimonials
- A working contact form

## Features

- 🎨 **Dark/light theme toggle** with a clean, modern design
- 📱 **Fully responsive** layout for desktop, tablet, and mobile
- 🧭 **Sticky navigation** with scroll-spy highlighting for the active section
- 🗂️ **Filterable project gallery** (Flutter, Python, C++, Academic)
- 📊 **Animated skill proficiency rings** and stat counters
- 📩 **Contact form** powered by [Formspree](https://formspree.io/)
- ⬆️ **Back-to-top** button and smooth scroll behavior
- 🔍 **SEO-ready** with meta tags, sitemap, and structured data (JSON-LD)
- 🖼️ Custom favicons, app icons, and Open Graph image for social sharing

## Tech Stack

| Layer      | Technology                     |
|------------|---------------------------------|
| Markup     | HTML5                           |
| Styling    | CSS3 (custom properties, no framework) |
| Behavior   | Vanilla JavaScript (ES6+)       |
| Forms      | Formspree                       |
| Hosting    | Static hosting (GitHub Pages / infinity free / mdanyal.page.gd) |

## Project Structure

```
MDK_Portfolio/
├── assets/                # Images, icons, favicons, and resume (CV)
│   ├── android-chrome-*.png
│   ├── apple-touch-icon.png
│   ├── cv.pdf
│   ├── favicon*.png / .ico
│   ├── og-image.jpg
│   └── profile.png / .webp
├── index.html              # Main HTML page (all sections)
├── styles.css               # Global styles and theming
├── script.js                 # Interactivity: nav, theme, filters, form, animations
├── site.webmanifest           # PWA manifest
├── sitemap.xml                 # SEO sitemap
├── robots.txt                   # Search engine crawl rules
└── README.md
```

## Getting Started

No build process is required — this is a static site.

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/mdanyal-khan/MDK_Portfolio.git
   cd MDK_Portfolio
   ```
2. Open `index.html` directly in your browser, **or** serve it locally for the best experience (recommended, so relative paths and manifest load correctly):
   ```bash
   # Using Python
   python3 -m http.server 8000

   # Or using Node's http-server
   npx http-server .
   ```
3. Visit `http://localhost:8000` in your browser.

### Deployment

Being a static site, it can be deployed to any static hosting provider, for example:

- **GitHub Pages** — enable Pages in the repository settings and point it to the `main` branch.
- **Netlify / Vercel** — import the repository and deploy with default static site settings (no build command needed).

## Customization

- **Contact form:** Update the `action` URL in the `<form id="contactForm">` element in `index.html` with your own [Formspree](https://formspree.io/) endpoint (or another form backend).
- **Projects:** Add or edit entries inside the `<ul class="projects-grid">` section in `index.html`, using the existing `data-category` values (`flutter`, `python`, `cpp`, `academic`) to keep filtering working.
- **Skills:** Adjust proficiency by editing the `--proficiency` CSS variable on each `.skill-card`.
- **Theme colors:** Modify the CSS custom properties defined at the top of `styles.css`.

## Contact

- **Email:** [mdanyal.khan42@gmail.com](mailto:mdanyal.khan42@gmail.com)
- **LinkedIn:** [Muhammad Danyal](https://www.linkedin.com/in/muhammad-danyal-5564a7376/)
- **GitHub:** [@mdanyal-khan](https://github.com/mdanyal-khan)
- **WhatsApp:** [+92 313 9709274](https://wa.me/923139709274)

## License

This project is currently unlicensed. If you'd like others to be free to reuse or adapt this portfolio template, consider adding an open-source license such as [MIT](https://choosealicense.com/licenses/mit/).

---

<p align="center">Designed & built by Muhammad Danyal Khan</p>
