# Nakul Patel - Old Portfolio Website

My earlier developer portfolio, kept as an archive and no longer developed; only the resume PDF still gets updated. Built with plain HTML, CSS and JavaScript, it covers my projects, skills and experience with an animated particle background, an "About" photo carousel, an experience timeline and a code-editor-style skills section.

**Live (old version) at [nakulpatel0306.github.io/portfolio-website-archive](https://nakulpatel0306.github.io/portfolio-website-archive/)**

## At a Glance

- **Stack:** HTML, CSS and JavaScript. No framework or build step
- **Hosting:** GitHub Pages, served from `main`
- **Resume:** [`assets/nakul-patel-software-resume.pdf`](assets/nakul-patel-software-resume.pdf) (last updated September 2026)
- **State:** Archived (old version), September 2026

## Features

- Responsive navigation with a mobile hamburger menu
- Animated particle background that reacts to the cursor
- About section carousel with keyboard and swipe support
- Projects grid with hover animations
- Experience timeline
- Skills shown in a code-editor-style block

## Project Structure

```
.
├── index.html            # Sections: Profile, About, Experience, Projects, Skills, Contact
├── style.css             # Layout, timeline, projects and skills styling
├── mediaqueries.css      # Responsive styles for mobile, tablet and desktop
├── script.js             # Menu toggle, animations, typewriter, carousel, effects
└── assets/               # Images, icons and resume PDF
```

## Running Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/nakulpatel0306/portfolio-website-archive.git
   cd portfolio-website-archive
   ```
2. Open `index.html` in your browser, or start a local server:
   ```bash
   python3 -m http.server 5173
   ```
   Then visit `http://localhost:5173`.
