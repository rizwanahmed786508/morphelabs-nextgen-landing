<div align="center">

# 🌌 MorpheLabs — AI Agency Landing Page Redesign

### A modern, single-page website for an AI automation & software development agency

<p align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)
![Frontend](https://img.shields.io/badge/Frontend-Project-orange?style=for-the-badge)
![Single%20Page](https://img.shields.io/badge/Single%20Page-Landing%20Page-blueviolet?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

Built with **HTML, CSS & JavaScript** — no frameworks, no build step, one file.

</div>

<br>

## 📖 Project Overview

**MorpheLabs Website Redesign** is a premium, single-page landing page built for an AI Automation and Software Development agency. The project reimagines a demo site into a modern, dark-mode, glassmorphic experience inspired by premium SaaS products like Vercel, Stripe, Linear, and Framer.

It showcases MorpheLabs' core offerings — AI Agents, Voice Agents, Chatbots, Workflow Automation, Web & Mobile Development, Lead Generation, and SEO — through an animated hero, interactive service cards, case studies, testimonials, and a working contact form, all inside a **single self-contained `index.html` file**.

This project was built as a **portfolio-quality front-end design and engineering exercise**, demonstrating:
- Modern visual design systems (glassmorphism, gradients, aurora backgrounds)
- Vanilla JS interactivity without any framework overhead
- Accessible, responsive, production-minded front-end code

---

## ✨ Features

- 🎨 **Premium dark-mode UI** — glassmorphism, aurora gradients, neon accent palette
- 🌀 **Signature morphing brand mark** — animated SVG blob reflecting the "Morphe" (transform) identity
- ⚡ **Animated loading screen** with logo fade-in/out
- 📊 **Scroll progress bar** at the top of the viewport
- 🧭 **Scroll-spy navigation** — active nav link highlights based on scroll position
- 🖱️ **Micro-interactions** — button ripple effects, card hover lifts, icon animations
- 📈 **Animated statistics counters** triggered on scroll
- 🗂️ **Dynamic content rendering** — services, solutions, case studies, testimonials, and FAQ generated from JS data objects
- ❓ **Accessible FAQ accordion** with `aria-expanded` / `aria-controls`
- 📬 **Working front-end contact form** with a success-state animation
- 🔝 **Back-to-top button**
- 📱 **Fully responsive** — desktop, tablet, and mobile layouts
- ♿ **Accessibility-conscious** — skip link, focus states, reduced-motion support, semantic structure
- 🔍 **SEO-ready** — Open Graph and Twitter Card meta tags, favicon, theme color

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Layout, responsive design, animations, glassmorphism effects |
| **JavaScript (Vanilla ES6+)** | Interactivity, DOM rendering, scroll effects, form handling |
| **SVG** | Icons, brand mark, and the animated morphing hero graphic |
| **Canvas API** | Ambient background particle animation |
| **Fontshare (Clash Display + Satoshi)** | Typography |

No frameworks, build tools, or external JS libraries are required.

---

## 📁 Project Structure

```
morphelabs-website-redesign/
│
├── index.html          # Entire site — HTML, CSS, and JS in a single file
└── README.md            # Project documentation
```

> The entire site — markup, styles, and scripts — lives in one `index.html` file for simplicity and portability.

---

## ⚙️ Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/rizwanahmed786508/morphelabs-website-redesign.git
cd morphelabs-website-redesign
```

No dependencies or package installation required.

---

## 💻 Local Usage

Since the project is a single static HTML file, you can run it in any of the following ways:

**Option 1 — Open directly in a browser**
```bash
open index.html        # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

**Option 2 — Serve with a local development server (recommended)**
```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000` in your browser.

---

## 🚀 Deployment on Vercel

This project can be deployed on [Vercel](https://vercel.com) in minutes, with zero configuration:

1. Push this repository to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Framework Preset: select **Other** (no build step needed).
4. Leave the **Build Command** empty and set the **Output Directory** to `./`.
5. Click **Deploy**.

Vercel will detect `index.html` and serve it as a static site automatically.

Alternatively, deploy via the Vercel CLI:

```bash
npm i -g vercel
vercel
```

---

## 📱 Responsive Design

The layout is fully responsive across all standard breakpoints:

| Device | Breakpoint | Behavior |
|---|---|---|
| Desktop | `> 1080px` | Full multi-column grid layout |
| Tablet | `≤ 1080px` | Two-column grids, adjusted section spacing |
| Mobile | `≤ 760px` | Single-column stacked layout, slide-in navigation menu |

All typography, spacing, and interactive elements scale fluidly using `clamp()` and CSS Grid/Flexbox.

---

## 🌐 Browser Compatibility

Tested and optimized for the latest versions of:

- ✅ Google Chrome
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari (macOS & iOS)

> Uses modern CSS (Grid, `backdrop-filter`, custom properties) and JavaScript (`IntersectionObserver`, ES6+). A modern evergreen browser is recommended for full visual fidelity.

---

## 🔮 Future Improvements

- [ ] Connect the contact form to a real backend or form service (e.g., Formspree, EmailJS)
- [ ] Add a CMS-driven content layer for services, case studies, and testimonials
- [ ] Introduce dark/light theme toggle
- [ ] Add real client logos, case study data, and team photos
- [ ] Migrate to a component-based framework (React/Next.js) for scalability
- [ ] Add automated accessibility and Lighthouse CI checks

---

## 🖼️ Screenshots

> _Add screenshots of the site here once available._

| Section | Preview |
|---|---|
| Hero | `screenshots/hero.png` |
| Services | `screenshots/services.png` |
| Solutions | `screenshots/solutions.png` |
| Case Studies | `screenshots/case-studies.png` |
| Contact | `screenshots/contact.png` |

---

## 🔗 Live Demo

> _Add your deployed Vercel link here._

**Live Site:** [https://your-project-name.vercel.app](https://your-project-name.vercel.app)

---

## 🏷️ GitHub Topics

```
html css javascript landing-page website-design ai-agency
responsive-design frontend web-development glassmorphism ui-ux single-page-application
```

---

## 📌 Internship Task

This project was completed as part of the **MorpheLabs Frontend Internship Assessment**.

The objective was to redesign an AI agency landing page using only **HTML, CSS, and JavaScript** while maintaining a clean architecture, responsive layout, accessibility, and interactive user experience.

---

## 👨‍💻 Author

### Rizwan Ahmed

Software Engineering Student | Machine Learning & Data Science Enthusiast | Frontend Developer

- **GitHub:** https://github.com/rizwanahmed786508
- **LinkedIn:** https://www.linkedin.com/in/rizwanahmed78

---

<p align="center">
<img src="https://komarev.com/ghpvc/?username=rizwanahmed786508&label=Repository%20Views&color=0e75b6&style=flat" />
</p>

<div align="center">

If you found this project useful or interesting, consider giving it a ⭐

</div>
