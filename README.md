<div align="center">

<img src="public/project.png" alt="Astro Gallery – Project Screenshot" />

</div>

<div align="center">

![Astro](https://img.shields.io/badge/Astro-2.6-BC52EE?logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38BDF8?logo=tailwindcss&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?logo=typescript&logoColor=white)
![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?logo=vercel&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

## Overview

**Astro Gallery** is a minimal, blazing-fast photography portfolio website. It showcases a curated collection of photographs in a dynamic, alternating grid layout with staggered scroll-triggered animations. Built with Astro's static site generation, the site ships near-zero JavaScript to the browser, resulting in exceptional Lighthouse scores and a seamless viewing experience.

> Designed for photographer & filmmaker **Kareem Amged**, based in Amsterdam, The Netherlands.

---

## Key Features

- **Static Site Generation (SSG)** — Pre-rendered at build time for maximum performance and SEO.
- **Dynamic Image Gallery** — Images are auto-discovered via `Astro.glob()` from the `/public/images/` directory; adding a photo to the folder is all it takes.
- **Alternating Masonry Grid** — A 7-column desktop grid with alternating even/odd row spanning patterns for a professional editorial look.
- **Scroll-Triggered Animations** — Intersection Observer API drives staggered fade-in + slide-up animations per image, with calculated per-position delays.
- **Native Lazy Loading** — Each image uses `loading="lazy"` for optimal network performance.
- **Responsive Layout** — Mobile-first: single-column on small screens, 7-column editorial grid on `md`+ breakpoints.
- **Variable Typography** — [League Spartan Variable](https://fonts.google.com/specimen/League+Spartan) font with antialiased rendering and responsive sizing (32px → 50px).
- **Sticky Navigation** — Header with hover-state opacity transitions and minimal nav links.
- **Minimal JavaScript Footprint** — Astro's island architecture ensures JS is only loaded where strictly necessary.

---

## Tech Stack

| Technology | Role |
|---|---|
| [Astro 2.6](https://astro.build/) | Web framework & static site generator |
| [Tailwind CSS 3](https://tailwindcss.com/) | Utility-first styling |
| [TypeScript (strict)](https://www.typescriptlang.org/) | Type safety |
| [League Spartan Variable](https://fontsource.org/fonts/league-spartan) | Display typography |
| [Vercel](https://vercel.com/) | Deployment & hosting |

---

## Getting Started

### Prerequisites

- [Node.js v16+ (LTS recommended)](https://nodejs.org/en/)

### Recommended VSCode Extensions

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode)

### Installation

**1. Clone or [fork](https://github.com/kimooamigo/GalleryPhoto-Website/fork) the repository:**

```bash
git clone git@github.com:kimooamigo/GalleryPhoto-Website.git
