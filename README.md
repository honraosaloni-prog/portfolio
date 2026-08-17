Saloni Honrao — Portfolio

A single-page personal portfolio site for Saloni Honrao, a Computer Engineering student and frontend developer based in Pune, India. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step.

Overview
The site is a warm, editorial-style landing page that introduces Saloni, her skills, and her contact details in one smooth scroll. It's designed to feel elegant and personal rather than templated, with a cream-and-gold color palette, serif display type, and quiet scroll-triggered animations.

Live sections:

Hero — name, current roles, short bio, and quick-action buttons (skills / contact / resume)
About — background, focus areas, and a quick-facts table (location, degree, focus areas, availability, languages)
Skills — categorized tech stack: Frontend Development, AI Fundamentals, Engineering & Tools, and Soft Skills
Contact — email, LinkedIn, GitHub, and resume download, with a dark contrasting panel
Footer — availability status and copyright
Tech Stack
HTML5 — semantic single-file structure
CSS3 — custom properties (CSS variables) for theming, CSS Grid/Flexbox layout, keyframe animations, IntersectionObserver-driven scroll reveals
Vanilla JavaScript — custom cursor tracking, scroll-based nav shrink, reveal-on-scroll logic
Google Fonts — Cormorant Garamond (serif display) and Jost (body/UI)
No build tools, package managers, or dependencies are required — it's a single static HTML file.

Getting Started
Since this is a static site, you can run it locally with no setup:

bash
# Option 1: just open it
open portfolio.html   # macOS
# or double-click the file in your file explorer

# Option 2: serve it locally (recommended for consistent font/asset loading)
python3 -m http.server 8000
# then visit http://localhost:8000/portfolio.html
Project Structure
.
├── portfolio.html   # Entire site: markup, styles, and scripts in one file
└── README.md
Customizing
All content lives directly in portfolio.html:

To change...	Look for...
Name / hero text	#hero section
About Me copy & quick facts	#about section, .about-rows
Skills & tech stack	#skills section, .skill-cat blocks
Contact links (email, socials)	#contact section, .contact-item links
Resume download link	download anchor tags (currently placeholder href="#")
Colors / theme	:root CSS variables at the top of the file
Note: The résumé download buttons currently use placeholder href="#" links. Update these to point to an actual hosted PDF (e.g. resume.pdf) before deploying.

Deployment
Being a static single-file site, it can be deployed anywhere that serves static assets:

GitHub Pages — push to a repo and enable Pages on the branch
Netlify / Vercel — drag-and-drop deploy or connect the repo
Any static file host (S3, Cloudflare Pages, Firebase Hosting, etc.)
Contact
Email: honraosaloni@gmail.com
LinkedIn: linkedin.com/in/saloni-honrao-5822a8316
GitHub: github.com/honraosaloni-prog
© 2025 Saloni Honrao · Built with care




