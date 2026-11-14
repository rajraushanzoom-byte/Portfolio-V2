# Portfolio-V2
# Portfolio V2 — Raj Raushan

My personal portfolio website, built from scratch with **HTML, CSS and vanilla JavaScript** (no frameworks, no libraries).

**Live demo:** https://rajraushanzoom-byte.github.io/Portfolio-V2/

## About

Instead of a static page, this portfolio has six animated "agent" cursors (Typesetr, Copy, Layout, Motion, QA and Review) that move around the page. They draw selection boxes, crop and build each section as you scroll, and leave small edit notes like a design team working live. A single button in the bottom bar stops or starts them.

## Features

- Dark, responsive design for phone, tablet and desktop
- Scroll-triggered reveal animations written in plain JavaScript
- Live GitHub repo count fetched from the GitHub API
- Sections for projects, education, skills and contact
- Stop / Start toggle for the agent animations
- Respects `prefers-reduced-motion`
- Safe-area support for phones with notches
- Optional profile photo upload (client-side preview only)

## Tech stack

- HTML5
- CSS3 (custom properties, grid, flexbox, `backdrop-filter`)
- JavaScript (ES6+)
- GitHub REST API
- Google Fonts (Anton, Inter, JetBrains Mono)
- Hosted on GitHub Pages

## Project structure

```
Portfolio-V2/
├── index.html      # the whole site: markup, styles and scripts
├── scaler-logo.png # optional, education logo
├── iitm-logo.png   # optional, education logo
└── README.md
```

The logo images are optional. If a file is missing, the page hides that image automatically.

## Run locally

1. Clone the repo
   ```bash
   git clone https://github.com/rajraushanzoom-byte/Portfolio-V2.git
   cd Portfolio-V2
   ```
2. Open `index.html` in your browser. No build step or install needed.

## Deploy on GitHub Pages

1. Push the project to a GitHub repository
2. Go to **Settings → Pages**
3. Under **Source**, choose the `main` branch and the `/ (root)` folder
4. Save, and your site will be live in a minute or two

## Other projects

| Project | Description |
| --- | --- |
| [Question Vault](https://rajraushanzoom-byte.github.io/Question-Vault/) | Mock-test platform with Firebase sign-in and optional AI question cleanup |
| [YouTube Clone](https://rajraushanzoom-byte.github.io/my-project-youtube-clone/) | Responsive copy of the YouTube home page |
| [The Last Floor](https://rajraushanzoom-byte.github.io/THE-LAST-FLOOR/) | Browser game (in progress) |
| [Routine Tracker](https://rajraushanzoom-byte.github.io/Routine-Tracker/) | Daily routine app with a check-in calendar (in progress) |

## Contact

- GitHub: [@rajraushanzoom-byte](https://github.com/rajraushanzoom-byte)
- LinkedIn: [Raj Raushan Kumar](https://www.linkedin.com/in/raj-raushan-kumar-4a2b07406/)
- Instagram: [@raj_raushan578](https://www.instagram.com/raj_raushan578)

## License

© 2026 Raj Raushan Kumar. All rights reserved.
