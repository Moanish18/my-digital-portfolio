My Digital Portfolio

The personal portfolio of me.

✦ About this site
This is a single-page personal portfolio designed in an editorial dark aesthetic — think magazine cover meets terminal. It's built to showcase a career that spans AI engineering, RPA, cloud infrastructure, full-stack development, and business analysis.
Design direction

Typography: Fraunces (display serif) + JetBrains Mono (technical text). Two-font discipline throughout.
Palette: Near-black #0c0b09 background, cream #f4ede0 ink, hot amber #e85d2c accent, gold #c89a3c for special moments.
Motion: CSS-only — staggered hero reveals, scroll-triggered fade-ups, infinite credential marquees, hover state surprises.
Texture: Film-grain SVG overlay for atmosphere. No gradients, no glass-morphism, no AI-template clichés.


✦ What's inside
The site is structured as a deliberate read, top to bottom:
#SectionPurpose00HeroName, role tags, portrait, current status, the floating 500+ typographic mark★Featured RibbonSUTD offer + 500-cert / IBM AI Engineer milestone01AboutDrop-cap intro, pull-quote, real stats grid02CredentialsVendor grid (AWS, IBM, Cisco, Google, Microsoft, MongoDB, NVIDIA, ...) + two scrolling marquees03Selected Work12 shipped projects with stack tags, organisation, and impact metrics04ExperienceAccenture · Mandai (×2) · MIRAE · Alphaeus, with recognition callouts04.5RecommendationPull-quote from Mark Teo (AVP, Transformation Office, Mandai Wildlife Group)05ToolkitSix-block skills matrix across AI/ML, Cloud, RPA, Data, Security, Web06EducationSUTD (incoming) · Temasek Polytechnic · Deyi Secondary · Zhonghua Primary07PressFeatured in Mandai's Innovation Talent Programme article (Mar 2026)✉ContactLinkedIn · GitHub · Credly · Email

✦ Tech stack
Deliberately minimal. No framework, no build, no dependencies.

HTML5 — single index.html file, semantic markup
CSS3 — custom properties, grid, flexbox, scroll-driven animations, clamp()-based fluid typography
JavaScript — one IntersectionObserver for scroll-reveal. That's it.
Google Fonts — Fraunces + JetBrains Mono loaded via <link>
One image asset — moanish.jpg (headshot)
Inline SVG favicon — no separate .ico file needed

The entire site is under 60 KB of HTML, weighs in at ~1700 lines of source, and loads instantly anywhere on earth.

✦ Running it locally
No build step. No npm install. No webpack config to fight.
bash# Clone the repo
git clone https://github.com/Moanish18/my-digital-portfolio.git
cd my-digital-portfolio

# Option 1 — just open the file
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux

✦ Deployment
The portfolio is deployed via GitHub Pages. To replicate:

Push to a public GitHub repo
Go to Settings → Pages
Set source to main branch, root folder (/)
Wait ~30 seconds. Site goes live at https://<username>.github.io/<repo-name>/

Alternatively, drag-and-drop index.html + moanish.jpg onto Netlify Drop for instant deployment with a custom URL.

✦ Customising for yourself
If you're forking this for your own portfolio, here's what to change:
File / sectionWhat to update<title> and meta tagsYour name and descriptionOpen Graph tagsYour name, description, and OG imageHero <h1>Your name with the italic splitHero sidebarYour current role, holdings, statusmoanish.jpgYour headshot (same filename or update the <img src>)Featured ribbonYour two biggest milestonesAbout bodyYour story, your quote, your statsCredentials sectionYour vendor grid and chip listsProjectsYour shipped work, with real impact metricsExperienceYour roles, in reverse chronological orderRecommendationA real quote from a real reference (or remove the section)Skills matrixYour actual stackEducationYour schoolsPress sectionReal third-party features only — remove if noneContact linksYour real LinkedIn, GitHub, Credly, email
The CSS custom properties at the top of <style> let you re-theme the entire site by editing a single block:
css:root {
  --bg: #0c0b09;        /* background */
  --paper: #f4ede0;     /* primary text */
  --accent: #e85d2c;    /* hot accent — change this for a different vibe */
  --gold: #c89a3c;      /* secondary highlight */
  /* ... */
}

✦ Browser support
Tested and works on:

Chrome / Edge 100+
Firefox 100+
Safari 15+ (macOS and iOS)
Mobile browsers — responsive down to 360px width

Uses modern CSS features like aspect-ratio, clamp(), CSS custom properties, and backdrop-filter. Falls back gracefully on older browsers but is best viewed on anything from the last ~3 years.

✦ Accessibility notes

Semantic HTML throughout (<nav>, <section>, <article> where appropriate)
Alt text on the portrait
Sufficient contrast ratios on all text (WCAG AA on body copy, AAA on most)
Keyboard-navigable — every link is reachable via tab
Reduced motion not yet wired in — future improvement


✦ Roadmap
Potential additions, in rough priority order:

 prefers-reduced-motion support to disable marquees for users who need it
 PDF resume download button
 Live GitHub repo stats via the GitHub API
 Blog section (only if I have posts ready — empty blogs hurt more than no blog)
 Dark/light theme toggle (currently dark-only by design)
 More project case-study pages on hover or modal expand


✦ Credits & inspiration

Fonts: Fraunces by Undercase Type, JetBrains Mono by JetBrains
Recommendation: Mark Teo Jun Yi, AVP Transformation Office at Mandai Wildlife Group — for the letter that made the recommendation section possible
Feature: Mandai Wildlife Group's Innovation Talent Programme article
Design philosophy: Refined editorial maximalism. Bold typography, intentional whitespace, no generic AI-template aesthetics.

✦ License
The portfolio code is shared for reference. If you want to use the structure for your own portfolio, feel free to fork — but please replace all personal content (name, photo, projects, recommendation, etc.) with your own.
The Mandai Wildlife Group recommendation letter content, the Mandai feature quote, and the personal photo are © Moanish Ashok Kumar and not reusable.
