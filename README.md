# Bruma — Editorial Coffee Landing

Demo landing page for **Bruma**, a fictional specialty coffee roaster. Magazine-style editorial design, warm and organic, with an asymmetric layout and narrative scroll animations.

> **Frontend-only demo.** There is no backend, store, cart or API. Products, prices, farms and contact details are fictional. The goal is to show visual and motion skills.

## Stack

- **Astro** (static site)
- **SCSS / vanilla CSS** (per-component styles, no utility framework)
- **GSAP** + **ScrollTrigger** for the scroll animations
- **Lenis** for smooth scroll with inertia

## Design

- **Earth palette:** cream (`#F4ECE0`), dark coffee (`#3B2A1E`), terracotta (`#C2683D`) and olive as an accent.
- **Typography:** Fraunces (variable display serif) for headlines + Hanken Grotesk (humanist sans) for body text.
- **Layout:** asymmetric editorial, lots of whitespace, giant numerals and full-bleed sections.
- **Film grain** texture over the whole page for a paper feel.

## Animations

- Hero headline reveal **line by line** (mask + translate).
- **Parallax** on the illustrated panels.
- **Image reveal with clip-path** on entering the viewport.
- **Smooth scroll** with inertia (Lenis synced with ScrollTrigger).
- **Marquee** of tasting notes.
- Staggered reveals of blocks and cards.
- Respects `prefers-reduced-motion`.

## Sections

Full-screen editorial hero · Story / origin · Roasting process (4 steps) · Notes marquee · Featured products · Location · Footer.

The images are illustrations built with CSS (gradients, clip-path and inline SVG); no real photos are used.

## Development

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs dist/
```
