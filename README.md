# MoneyMentor

A static, multi-page marketing website for a financial advisory agency. Built with vanilla HTML, CSS, and JavaScript—no frameworks or build step required.

## Overview

**MoneyMentor** is a professional landing experience for a financial advisory brand. It includes:

- **Landing page** — Hero, services, projects, about, CTA, blog section, and contact form
- **Auth** — Responsive sign-in and sign-up form with sliding panels
- **Chatbot** — Embedded TARS (HelloTars) lead-generation chatbot for financial advisors

The site is fully static and runs in any modern browser. No backend, database, or build tools are used.

---

## Project Structure

```
MoneyMentor/
├── index.html              # Main landing page
├── favicon.svg
├── README.md
├── assets/
│   ├── css/
│   │   └── style.css       # Main styles
│   ├── js/
│   │   └── script.js      # Header, nav, back-to-top
│   └── images/             # Image assets
├── auth/
│   ├── index.html          # Sign In / Sign Up page
│   ├── style.css
│   ├── app.js              # Sliding form logic
│   └── img/
│       ├── log.svg
│       └── register.svg
└── chatbot/
    └── index.html          # TARS chatbot embed (iframe)
```

---

## Tech Stack

| Area    | Stack                                |
|---------|--------------------------------------|
| Markup  | HTML5                                |
| Styling | CSS3 (custom properties, grid)      |
| Script  | Vanilla JavaScript (ES5+)           |
| Fonts   | Google Fonts (League Spartan, Roboto)|
| Icons   | Ionicons 5.5.2, Font Awesome (auth)  |
| Chatbot | TARS / HelloTars (iframe)            |

No package manager, bundler, or Node.js required.

---

## Getting Started

### Open directly

Open `index.html` in a browser. For correct routing between pages, use a local server.

### Local server (recommended)

**Python 3:**
```bash
python -m http.server 8000
```

**Node (npx):**
```bash
npx serve .
```

Then visit:

- **Home:** `http://localhost:8000/`
- **Sign In / Sign Up:** `http://localhost:8000/auth/`
- **Chatbot:** `http://localhost:8000/chatbot/`

---

## Image Assets

The main page references images under `assets/images/`. Add these files (or update paths as needed):

| File              | Usage          |
|-------------------|----------------|
| `hero-banner.png` | Hero section   |
| `project-1.jpg` … `project-6.jpg` | Project cards |
| `about-banner.jpg` | About section |
| `cta-bg.jpg`      | CTA background |
| `blog-1.jpg` … `blog-5.jpg` | Blog cards |

---

## Features

- **Responsive layout** — Mobile-first with breakpoints (575px, 768px, 992px, 1200px)
- **Sticky header** with scroll effect and mobile nav toggle
- **Smooth scrolling** and back-to-top button
- **Auth page** — Sliding Sign In / Sign Up with social login placeholders
- **Chatbot** — Full-page iframe to TARS financial advisor chatbot
- **Contact form** — Client-side form (connect to your backend as needed)
- **External links** — Life Goals Quiz, Get Started, and partner sites (Upstox, Groww, etc.)

---

## License

This project is for demonstration purposes. Check individual assets and third-party services (TARS, fonts, icons) for their respective licenses.

---

## Credits

- **Author:** [Vishal Patil](https://vishaltechnotes.blogspot.com/)
