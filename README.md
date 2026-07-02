# Vedansh Prakash — Portfolio

A single-page, dark-themed developer portfolio for **Vedansh Prakash**, a Computer Science graduate (B.Tech, AKTU) specializing in Software Engineering and AI/ML. Built as a self-contained static HTML file with a terminal-inspired, engineering-focused aesthetic.

🔗 **Live status:** Available for full-time roles in Software Engineering, Backend Development, or ML/Data.

---

## Overview

This portfolio is designed to read like a technical résumé with production-grade design polish — grid backgrounds, ambient glow effects, monospace accents, and subtle animations — rather than a generic template. It's built to make the case for hiring through evidence: real metrics, real deployed projects, and real ownership of end-to-end systems.

## Tech Stack

- **Pure HTML5 / CSS3** — no framework, no build step
- **Google Fonts**: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (display), [Inter](https://fonts.google.com/specimen/Inter) (body), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (code/mono accents)
- CSS custom properties (`:root` variables) for a consistent dark theme (blue / purple / amber / green accent palette)
- Fully responsive grid layouts (`grid-template-columns`, `auto-fit`, `minmax`)
- Scroll-based smooth navigation and CSS-only micro-animations (blinking cursor, pulsing status dot, hover states)

## Sections

| Section | Contents |
|---|---|
| **Hero** | Name, role, elevator pitch, CTAs (See My Work / Hire Me / LinkedIn / LeetCode / GFG / CodeChef), and a 4-stat metric bar (production apps, ML accuracy, malware detection rate, DSA problems solved) |
| **About** | Background summary, location, degree, primary stack, roles open to, GitHub & email |
| **Why Hire Me** | Three value-proposition cards: Systematic Debugger, Full-Stack ML + Backend, Ownership Mindset |
| **Experience** | Internships — Java Programmer @ CodSoft, Web Developer @ InternPe |
| **Projects** | Featured: **Malware Mutation Detector** (LightGBM, EMBER dataset, 90% detection accuracy, live deployment). Plus: Email Spam Detector (99.3% SVM accuracy), Stock Price Predictor (5-model forecasting benchmark), Friday Voice Assistant (Flask + NLP microservice) |
| **Skills** | Grouped by category — Languages, ML/AI, Backend, Frontend, Data Libraries, Databases, Core CS, Tools & DevOps |
| **Education** | B.Tech CSE (2022–2026), Class XII & X (CBSE) |
| **Certifications** | Google (Generative AI, LLMs, Responsible AI), Simplilearn, HackerRank, Deloitte job simulations |
| **Contact** | Email, LinkedIn, GitHub, phone, location & availability |

## File Structure

```
Portfolio.html   # Single self-contained file — HTML, CSS, and assets all inline
```

No external build tools, package managers, or dependencies are required beyond an internet connection for the Google Fonts CDN link.

## Running Locally

Since this is a static single-file site, no server or build process is required:

```bash
# Just open it directly in a browser
open Portfolio.html      # macOS
start Portfolio.html     # Windows
xdg-open Portfolio.html  # Linux
```

Or serve it locally for a closer-to-production preview:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/Portfolio.html
```

## Deployment

Being a static HTML file, it can be deployed as-is to any static host:

- **GitHub Pages** — push to a repo and enable Pages on the `main` branch
- **Netlify / Vercel** — drag-and-drop deploy or connect the repo
- **Render / Cloudflare Pages** — similar static-site deploy flow

> One of the featured projects (Malware Mutation Detector) is already live at `glb-ai-mal-proj.onrender.com`, deployed via Render.

## Customization Notes

- All theme colors are defined as CSS variables in `:root` at the top of the `<style>` block (`--blue`, `--purple`, `--amber`, `--green`, etc.) — update these to re-theme the whole site.
- Section content (projects, skills, experience, certifications) is hard-coded directly in the HTML markup; update the relevant `<section>` blocks to change copy.
- Metrics in the hero stat bar and project stat rows should be kept accurate/up to date as new projects ship.

## Contact

- **Email:** vedansh1809@gmail.com
- **Phone:** +91 8173073528
- **Location:** Kanpur, Uttar Pradesh, India — open to relocation & remote work
- **GitHub:** [github.com/VEDANSHPRAKASH](https://github.com/VEDANSHPRAKASH)

---

© 2026 Vedansh Prakash · Built to get hired
