<div align="center">

# 🎨 Portfolio v3

3D portfolio — moncy.dev inspired, Three.js animated character. Hosted on Vercel.

![React](https://img.shields.io/badge/React-blue?logo=react) ![Three.js](https://img.shields.io/badge/Three.js-black?logo=three.js) ![Vercel](https://img.shields.io/badge/Vercel-deployed-black?logo=vercel) ![Last Commit](https://img.shields.io/github/last-commit/ehansih/portfolio-v3)

</div>

---

# Portfolio V3 — 3D Edition

Personal portfolio of **Harsh Vardhan Singh Chauhan** with a live 3D animated character in the hero, inspired by [moncy.dev](https://www.moncy.dev/).

## Live Preview
Deploy yourself on Vercel — see instructions below.

## Design
Matches the aesthetic of moncy.dev:
- **Background**: `#0b080c` deep dark purple-black
- **Accent**: `#c2a4ff` lavender purple
- **Font**: Geist (by Vercel)
- **3D**: Three.js WebGL character with wave + idle animation
- **FX**: Animated pink/purple glow circles, rim light, bottom fade, mouse parallax

## Features
- **3D animated character** — Three.js GLB model with wave → idle animation, mouse-follow parallax, rim glow
- Loading screen with progress bar
- Custom animated cursor with ring
- Animated glowing blur circles (moncy.dev-style hero)
- Hero: "Hello! I'm / HARSH VARDHAN" left + "A Telecom / Security Leader" right
- Scroll-reveal animations (Intersection Observer)
- Services hover list
- Career timeline (16+ years)
- GitHub projects grid (9 repos)
- Photography placeholder section
- Contact form via Formspree
- Fully responsive

## Tech Stack
- **HTML5 / CSS3 / Vanilla JS** — zero frameworks, zero build tools
- **Three.js** — loaded via CDN (importmap)
- **GLTFLoader + DRACOLoader** — for 3D model
- **Vercel** — deployment

## Replacing the 3D Model
The default model is `RobotExpressive.glb` from Three.js examples. To use your own:

1. Download a `.glb` character from [Mixamo](https://www.mixamo.com) or [Sketchfab](https://sketchfab.com)
2. Place it in this folder as `character.glb`
3. In `index.html`, change the model URL to `./character.glb`
4. Adjust `model.scale` and `model.position.y` to fit

## Deploy to Vercel

```bash
npm i -g vercel
vercel --prod
```

Or connect this GitHub repo directly in the Vercel dashboard.

## Sections
- Hero (3D character + split text)
- About + Stats
- Areas of Expertise
- Career Journey
- GitHub Projects
- Photography
- Contact

## Author
**Harsh Vardhan Singh Chauhan**
- LinkedIn: [linkedin.com/in/harsh-vardhan-75865121](https://www.linkedin.com/in/harsh-vardhan-75865121/)
- GitHub: [github.com/ehansih](https://github.com/ehansih)
- Medium: [medium.com/@vardhan.chauhan](https://medium.com/@vardhan.chauhan)
- Email: vardhan.chauhan@icloud.com
