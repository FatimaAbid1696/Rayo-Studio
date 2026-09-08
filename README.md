# Rayo Studio — React Clone

A single-page React recreation of the Rayo Envato template, rebuilt with the same
cream / violet / lime color system and typography, plus an animated intro loader
(0→100% counter → curtain reveal), scroll-triggered reveals, 3D tilt-on-hover
cards, infinite marquees, and a full-screen animated menu.

![Node](https://img.shields.io/badge/node-%3E%3D18-brightgreen)
![React](https://img.shields.io/badge/react-19-blue)
![Vite](https://img.shields.io/badge/vite-6-purple)

## ✨ Features

- **Animated intro loader** — counts 0→100%, then a black curtain wipes up to reveal the hero
- **Full-screen menu** — circular clip-path reveal with staggered nav links
- **3D tilt cards** — spring-based cursor-tracking tilt across the showcase grids
- **Scroll-triggered reveals** — fade/slide-in animations as you scroll
- **Infinite marquees** — smooth looping text and card strips
- **Route transitions** — animated page transitions between Home and Contact
- **Fully responsive** — mobile, tablet, and desktop layouts

## 📄 Pages

- `/` — Hero, Works showcase, Blog/Portfolio split, Responsive/device section,
  About carousel, Stats marquee, Functional components, Features bento grid,
  CTA, Connect/office, Footer (all in one page)
- `/contact` — standalone contact page with a working client-side form

## 🛠 Tech Stack

- [React 19](https://react.dev/) + [Vite](https://vitejs.dev/)
- [React Router](https://reactrouter.com/) — route-level page transitions
- [Framer Motion](https://www.framer.com/motion/) — loader, curtain reveal, scroll reveals, tilt/hover interactions, marquees
- [Tailwind CSS v4](https://tailwindcss.com/) — design tokens in `src/index.css`
- [lucide-react](https://lucide.dev/) — icons

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18 or newer
- npm (comes with Node)

### Installation

```bash
git clone https://github.com/<your-username>/rayo-studio.git
cd rayo-studio
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Production Build

```bash
npm run build      # outputs to /dist
npm run preview    # preview the production build locally
```

## 🎨 Customizing

| What | Where |
|---|---|
| Colors & fonts | `src/index.css` (`@theme` block) — cream `#F6F1EC`, ink `#121212`, violet `#8C7EF5`, lime `#D8FF4F` |
| Loader timing | `src/components/Loader.jsx` |
| Section content/copy | Each section is its own file in `src/components/` |
| Images | `src/data/images.js` |

## 📂 Project Structure
