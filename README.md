My Digital Portfolio
> The personal portfolio of **Moanish Ashok Kumar** — Applied AI graduate from Temasek Polytechnic, incoming SUTD Design & AI student, Business Analyst Intern at Accenture, and holder of 500+ verified certifications.
🌐 Live site: Add your GitHub Pages URL here once deployed
![Built with HTML](https://img.shields.io/badge/Built%20with-HTML5-e85d2c?style=flat-square)
![No build step](https://img.shields.io/badge/Build%20step-None-0c0b09?style=flat-square)
![Single file](https://img.shields.io/badge/Single-File-c89a3c?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-4ade80?style=flat-square)
---
✦ About this site
This is a single-page personal portfolio designed in an editorial dark aesthetic — think magazine cover meets terminal. It's built to showcase a career that spans AI engineering, RPA, cloud infrastructure, full-stack development, and business analysis.
Design direction
Typography: Fraunces (display serif) + JetBrains Mono (technical text). Two-font discipline throughout.
Palette: Near-black `#0c0b09` background, cream `#f4ede0` ink, hot amber `#e85d2c` accent, gold `#c89a3c` for special moments.
Motion: CSS-only — staggered hero reveals, scroll-triggered fade-ups, infinite credential marquees, hover state surprises.
Texture: Film-grain SVG overlay for atmosphere. No gradients, no glass-morphism, no AI-template clichés.
---
✦ What's inside
The site is structured as a deliberate read, top to bottom:
#	Section	Purpose
00	Hero	Name, role tags, portrait, current status, the floating `500+` typographic mark
★	Featured Ribbon	SUTD offer + 500-cert / IBM AI Engineer milestone
01	About	Drop-cap intro, pull-quote, real stats grid
02	Credentials	Vendor grid (AWS, IBM, Cisco, Google, Microsoft, MongoDB, NVIDIA) + scrolling chips
03	Selected Work	12 shipped projects with stack tags, organisation, and impact metrics
04	Experience	Accenture · Mandai (×2) · MIRAE · Alphaeus, with recognition callouts
04.5	Recommendation	Pull-quote from Mark Teo (AVP, Transformation Office, Mandai Wildlife Group)
05	Toolkit	Six-block skills matrix across AI/ML, Cloud, RPA, Data, Security, Web
06	Education	SUTD (incoming) · Temasek Polytechnic · Deyi Secondary · Zhonghua Primary
07	Press	Featured in Mandai's Innovation Talent Programme article (Mar 2026)
✉	Contact	LinkedIn · GitHub · Credly · Email
---
✦ Tech stack
Deliberately minimal. No framework, no build, no dependencies.
HTML5 — single `index.html` file, semantic markup
CSS3 — custom properties, grid, flexbox, scroll-driven animations, `clamp()`-based fluid typography
JavaScript — one `IntersectionObserver` for scroll-reveal. That's it.
Google Fonts — Fraunces + JetBrains Mono loaded via `<link>`
One image asset — `moanish.jpg` (headshot)
Inline SVG favicon — no separate `.ico` file needed
The entire site is under 60 KB of HTML, weighs in at ~1700 lines of source, and loads instantly anywhere on earth.
---
✦ Running it locally
No build step. No `npm install`. No webpack config to fight.
```bash
# Clone the repo
git clone https://github.com/Moanish18/my-digital-portfolio.git
cd my-digital-portfolio

# Option 1 — just open the file
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux

# Option 2 — serve locally for a more accurate preview
python3 -m http.server 8000
# then visit http://localhost:8000
```
That's it. It's a static site in the truest sense.
---
✦ Deployment
The portfolio is deployed via GitHub Pages. To replicate:
Push to a public GitHub repo
Go to Settings → Pages
Set source to `main` branch, root folder (`/`)
Wait ~30 seconds. Site goes live at `https://<username>.github.io/<repo-name>/`
Alternatively, drag-and-drop `index.html` + `moanish.jpg` onto Netlify Drop for instant deployment with a custom URL.
---
✦ Customising for yourself
If you're forking this for your own portfolio, here's what to change:
File / Section	What to update
`<title>` and meta tags	Your name and description
Open Graph tags	Your name, description, and OG image
Hero `<h1>`	Your name with the italic split
Hero sidebar	Your current role, holdings, status
`moanish.jpg`	Your headshot (same filename or update the `<img src>`)
Featured ribbon	Your two biggest milestones
About body	Your story, your quote, your stats
Credentials section	Your vendor grid and chip lists
Projects	Your shipped work, with real impact metrics
Experience	Your roles, in reverse chronological order
Recommendation	A real quote from a real reference (or remove)
Skills matrix	Your actual stack
Education	Your schools
Press section	Real third-party features only — remove if none
Contact links	Your real LinkedIn, GitHub, Credly, email
The CSS custom properties at the top of `<style>` let you re-theme the entire site by editing a single block:
```css
:root {
  --bg: #0c0b09;        /* background */
  --paper: #f4ede0;     /* primary text */
  --accent: #e85d2c;    /* hot accent — change this for a different vibe */
  --gold: #c89a3c;      /* secondary highlight */
  /* ... */
}
```
---
✦ Browser support
Tested and works on:
Chrome / Edge 100+
Firefox 100+
Safari 15+ (macOS and iOS)
Mobile browsers — responsive down to 360px width
Uses modern CSS features like `aspect-ratio`, `clamp()`, CSS custom properties, and `backdrop-filter`. Falls back gracefully on older browsers but is best viewed on anything from the last ~3 years.
---
✦ Accessibility notes
Semantic HTML throughout (`<nav>`, `<section>`, `<article>` where appropriate)
Alt text on the portrait
Sufficient contrast ratios on all text (WCAG AA on body copy, AAA on most)
Keyboard-navigable — every link is reachable via tab
Reduced motion not yet wired in — future improvement
---
✦ Roadmap
Potential additions, in rough priority order:
[ ] `prefers-reduced-motion` support to disable marquees for users who need it
[ ] PDF resume download button
[ ] Live GitHub repo stats via the GitHub API
[ ] Blog section (only if I have posts ready — empty blogs hurt more than no blog)
[ ] Dark / light theme toggle (currently dark-only by design)
[ ] More project case-study pages on hover or modal expand
---
✦ Credits & inspiration
Fonts: Fraunces by Undercase Type, JetBrains Mono by JetBrains
Recommendation: Mark Teo Jun Yi, AVP Transformation Office at Mandai Wildlife Group — for the letter that made the recommendation section possible
Feature: Mandai Wildlife Group's Innovation Talent Programme article
Design philosophy: Refined editorial maximalism. Bold typography, intentional whitespace, no generic AI-template aesthetics.
---
✦ Get in touch
Channel	Link
LinkedIn	linkedin.com/in/moanish18
GitHub	github.com/Moanish18
Credly	credly.com/users/moanish.531fc0ec
Email	ishmoan@gmail.com
---
✦ License
The portfolio code is shared for reference. If you want to use the structure for your own portfolio, feel free to fork — but please replace all personal content (name, photo, projects, recommendation, etc.) with your own.
The Mandai Wildlife Group recommendation letter content, the Mandai feature quote, and the personal photo are © Moanish Ashok Kumar and not reusable.
---
<p align="center">
  <em>Built solo · Singapore · 2026</em><br>
  <code>v2.0 — single file — no dependencies</code>
</p>
