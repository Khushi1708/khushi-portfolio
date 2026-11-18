# Khushi Aggarwal — Portfolio

An interactive, multi-page developer portfolio for **Khushi Aggarwal**, B.Tech CSE (AI) student, full-stack developer and AI researcher. Built with plain HTML, CSS and JavaScript — no build step, no framework.

> **Live site:** add your Vercel URL here after deploying, e.g. `https://your-name.vercel.app`

## Features
- **3D neural-network background** (Three.js) with glowing pulses that react to the mouse and scroll
- **Aurora glass theme** with an animated gradient and tilt-on-hover cards
- **Multi-page navigation** — Home, About, Skills, Projects, Experience, Impact, Contact
- **Project case-study stories** — Problem → Build → Outcome tabs for each project
- **Experience storybook** — chapter-by-chapter slider (arrows or keyboard)
- **Clickable skills** — brief description plus where each skill was used, with search and category filters
- **Command palette** — `Ctrl/⌘ + K` or `/` to search pages, projects, experience and skills
- **Interactive terminal** on the home page (`help`, `projects`, `skill python`, `open skills`…)
- **Contact form** that opens a pre-filled email
- Responsive, scroll-progress bar, keyboard accessible, reduced-motion friendly

## Tech stack
HTML5 · CSS3 · JavaScript · Three.js (CDN) · Google Fonts (Fraunces, Inter, JetBrains Mono)

## Project structure
```
khushi-portfolio/
├── index.html    # the whole site (styles, content, scripts, photos)
├── favicon.svg   # site icon
├── vercel.json   # Vercel config
└── README.md
```

## Run locally
Open `index.html` in a browser, or serve the folder:
```
npx serve .
```

## Deploy to Vercel
**Dashboard (easiest)**
1. Unzip and push the `khushi-portfolio` folder to a new GitHub repository.
2. Go to https://vercel.com/new and import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**.

**CLI**
```
npm i -g vercel
cd khushi-portfolio
vercel --prod
```

## Customize
All content is in `index.html`:
- **Projects** and **experience** — the `var P=[...]` and `var E=[...]` arrays near the bottom
- **Skills** — the `var SK={...}` object (description and where it was used)
- **Live work links** — add URLs for Real Western Estates, Modiv and Tender Tots in the "Live work" cards on the Impact page
- **Colours** — CSS variables at the top of `<style>` (`--a`, `--b`, `--gr`)
- **Contact details** — search for `khushiaggarwal1708@gmail.com` and the LinkedIn / GitHub links

## Contact
- Email: khushiaggarwal1708@gmail.com
- LinkedIn: https://www.linkedin.com/in/khushi-aggarwal77
- GitHub: https://github.com/Khushi1708

## License
© 2026 Khushi Aggarwal. All rights reserved.
