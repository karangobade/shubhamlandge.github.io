# Shubham Landge — Portfolio

Personal portfolio site for a B.Tech AI & Data Science student, built to showcase machine learning and analytics projects to recruiters and hiring managers. Plain HTML/CSS/JS, no frameworks, no build step.

**Live site:** [shubhamlandge.github.io](https://shubhamlandge.github.io) *(update once deployed)*

---

## Overview

A dark-themed, fully responsive portfolio covering:

- **Hero** — animated intro with a typing-effect role headline and a canvas-drawn node graph background
- **About** — bio, current focus, quick stats
- **Skills** — grouped by domain (Programming / Data Analytics / AI & ML) with animated proficiency bars
- **Projects** — case-study cards with tech stack tags, measurable outcomes, and GitHub/demo links
- **Dashboard Gallery** — a dedicated page (`gallery.html`) with screenshots and write-ups of Power BI / analytics dashboards
- **Certificates** — issued-by, date, and score where applicable
- **Contact** — email, LinkedIn, GitHub, and a working `mailto:`-based contact form

## Design

The site color-codes three skill domains consistently across skill bars, project tags, and gallery entries:

| Domain | Color |
|---|---|
| Programming | `#F2B84B` (amber) |
| Data Analytics | `#2DD4BF` (teal) |
| AI & ML | `#A78BFA` (violet) |

Typography pairs **Space Grotesk** (headings), **Inter** (body), and **JetBrains Mono** (tags, stats, dates).

## Tech Stack

- HTML5, CSS3 (custom properties, CSS Grid/Flexbox, no framework)
- Vanilla JavaScript (Canvas API, IntersectionObserver, no dependencies)
- Google Fonts (Space Grotesk, Inter, JetBrains Mono)

## Project Structure

```
.
├── index.html              # Main portfolio page
├── gallery.html             # Dashboard gallery (screenshots + descriptions)
├── style.css                # All styling, responsive breakpoints
├── script.js                 # Typing effect, scroll reveal, skill bars, contact form
├── images/
│   ├── profile.jpg           # Profile photo
│   ├── project1.png ...      # Project screenshots
│   ├── dashboard1.png ...    # Dashboard gallery screenshots
│   ├── og-image.jpg          # Open Graph share image
│   └── favicon.svg
└── resume/
    └── resume.pdf
```

## Getting Started

No build step — clone and open directly.

```bash
git clone https://github.com/shubhamlandge/portfolio.git
cd portfolio
```

Then just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8080
# visit http://localhost:8080
```

## Deployment (GitHub Pages)

1. Push this repo to GitHub (name it `shubhamlandge.github.io` for a root-level URL, or any name for a project-page URL).
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder, then save.
4. Your site will be live at `https://<username>.github.io/` (or `/<repo-name>/`) within a couple of minutes.

## Customization Checklist

Before publishing, replace the placeholders:

- [ ] `images/profile.jpg`, `project1–3.png`, `dashboard1–4.png`, `og-image.jpg`
- [ ] `resume/resume.pdf`
- [ ] Email address, LinkedIn, and GitHub URLs in `index.html` and `gallery.html`
- [ ] Project GitHub/demo links (currently placeholder URLs)
- [ ] Skill proficiency percentages and project outcome metrics to reflect reality

## Accessibility & Performance

- Semantic HTML (`nav`, `header`, `main`, `section`, `footer`)
- Skip-to-content link, visible focus states, descriptive `alt` text throughout
- Lazy-loaded below-the-fold images, `preconnect` for font CDN
- Respects `prefers-reduced-motion` (disables animations/typing effect/canvas)

## Contact

- **Email:** shubham.landge@example.com
- **LinkedIn:** [linkedin.com/in/shubhamlandge](https://linkedin.com/in/shubhamlandge)
- **GitHub:** [github.com/shubhamlandge](https://github.com/shubhamlandge)

---

Built from scratch — no templates.
