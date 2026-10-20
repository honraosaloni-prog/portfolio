# Saloni Honrao — Personal Portfolio

> Elegant, animated single-file portfolio website built with vanilla HTML, CSS, and JavaScript.

---

🔗 **[Live Demo](https://honraosaloni-prog.github.io/portfolio/)**

---
## 👩‍💻 About

Personal portfolio of **Saloni Sudhakar Honrao**, a Computer Engineering student from Pune, India.  
Built to showcase projects, certificates, internship experience, and technical skills to recruiters across software development and data analytics roles.

---

## 📁 File Structure

```
saloni-portfolio.html   ← Entire portfolio (self-contained, single file)
README.md               ← This file
```

Everything — HTML, CSS, and JavaScript — lives in one file. No frameworks, no npm, no build tools.

---

## ✨ Features

- **Custom animated cursor** with a smooth lagging ring
- **Scroll-reveal animations** on every section using IntersectionObserver
- **Staggered entrance animations** on the hero section
- **Tabbed project switcher** — toggle between Software Development and Data Analytics projects
- **Sticky navbar** that shrinks on scroll with underline hover effect
- **Decorative portrait frame** with corner accents
- **Noise texture overlay** for depth
- **Fully responsive** — mobile-first layout with grid collapse
- **No JavaScript frameworks** — pure vanilla JS

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Name, role pills, bio, CTA buttons |
| **About** | Personal intro, SGPA, education summary, availability status |
| **Skills** | 5 categories: Languages, Frontend, Backend & APIs, Data Analytics, Security & Tools |
| **Projects** | Tabbed — 3 Software Dev + 3 Data Analytics projects with live/GitHub links |
| **Certificates** | 7 certificates split into 2 groups, all linked to Google Drive |
| **Experience** | 2 internships on a timeline |
| **Education** | B.E. + Diploma cards |
| **Contact** | Email, LinkedIn, GitHub links |

---

## 🚀 Projects

### Software Development
| Project | Links |
|---|---|
| **SecureDrop** — Encrypted browser-to-browser file transfer | [Live Demo](https://securedrop-8hje.onrender.com/) |
| **DataPermit** — Client-side sensitive data detection & redaction | [GitHub](https://github.com/honraosaloni-prog/DataPermit) |
| **DataLens** — AI-powered analytics dashboard | [Live Demo](https://datalens-mu.vercel.app/) |

### Data Analytics
| Project | Links |
|---|---|
| **GitHub Ecosystem Trends** — Language & AI tooling adoption analysis | [GitHub](https://github.com/honraosaloni-prog/github-ecosystem-trends) |
| **MHT-CET Cutoff Analysis** — Branch-level demand across 2022–2025 | [GitHub](https://github.com/honraosaloni-prog/mhtcet_cutoff_analysis) |
| **DataLens** — GenAI analytics dashboard | [Live Demo](https://datalens-mu.vercel.app/) |

---

## 🏅 Certificates

### Software Development & AI
| Certificate | Issuer | Date |
|---|---|---|
| Artificial Intelligence Fundamentals | IBM SkillsBuild | Mar 2026 |
| Introduction to OpenAI GPT Models | Infosys Springboard | Jan 2026 |
| Prompt Engineering | Infosys Springboard | Jan 2026 |

### Data Analytics & BI
| Certificate | Issuer | Date |
|---|---|---|
| GenAI Powered Data Analytics Job Simulation | Tata · Forage | Jun 2026 |
| Data Analytics Job Simulation | Deloitte · Forage | Aug 2026 |
| Data Visualisation: Empowering Business with Effective Insights | Tata · Forage | Aug 2026 |
| Data Fundamentals | IBM SkillsBuild | Jul 2026 |

---

## 🎨 Design

| Property | Value |
|---|---|
| **Color palette** | Cream `#faf8f4`, Ink `#1a1714`, Gold `#c9a96e` |
| **Fonts** | Cormorant Garamond (headings) · Jost (body) — via Google Fonts |
| **Style** | Elegant & professional — editorial serif meets clean sans-serif |
| **Theme** | Light only (cream background) |
| **Animations** | CSS keyframes + IntersectionObserver scroll reveal |

---

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, keyframe animations
- **Vanilla JavaScript** — cursor, scroll reveal, tab switcher, nav shrink
- **Google Fonts** — Cormorant Garamond + Jost
- Zero dependencies · Zero build tools · Zero frameworks

---

## 📬 Contact

| | |
|---|---|
| **Email** | honraosaloni@gmail.com |
| **LinkedIn** | [saloni-honrao-5822a8316](https://www.linkedin.com/in/saloni-honrao-5822a8316) |
| **GitHub** | [honraosaloni-prog](https://github.com/honraosaloni-prog) |
| **Location** | Pune, Maharashtra, India |

---

## 📝 Customisation Guide

To update the portfolio for future use:

1. **Add a photo** — Replace the `SH` monogram in `.portrait-fill` with an `<img>` tag pointing to your photo
2. **Update links** — Search for `href=` to find and update all project / certificate / contact links
3. **Add projects** — Copy a `.project-card` block inside the relevant `proj-panel` div
4. **Add certificates** — Copy a `.cert-card` block inside the relevant `.certs-grid` div
5. **Change colours** — Edit the CSS variables in `:root` at the top of the file
6. **Resume download** — Replace `href="#"` on the nav CTA and resume buttons with the actual PDF link

---

*Built with care · © 2025 Saloni Honrao*
