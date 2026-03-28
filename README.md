# Flamiee Termii

[![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react&logoColor=0B1020)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.x-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

A cinematic single-page React experience built around an expressive custom aesthetic, layered motion, playful interaction modes, and a typography-first visual identity.

## Overview

Flamiee Termii is a portfolio-style web experience implemented with Vite + React + TypeScript. It combines smooth scroll behavior, visual overlays, particle interactions, and an intentionally monospace-forward design language to create an immersive hero-to-footer flow.

## Features

- High-performance React SPA architecture with Vite bundling
- Motion-rich UI using Framer Motion, Lenis, and lightweight visual effects
- Interactive overlays and easter-egg behavior (Hacker/Coffee modes)
- Tailwind-driven design tokens and utility-first composition
- Responsive custom cursor, scroll progress, and ambient background systems
- Locally hosted custom typography via `@font-face` for brand-consistent rendering

## Tech Stack

- Framework: React 18
- Build Tool: Vite 7
- Language: TypeScript
- Styling: Tailwind CSS + custom CSS animations
- Motion/UX: Framer Motion, Lenis, GSAP, physics-inspired overlays

## Preview

### Footer Visual

![Flamiee Termii preview](./assets/footer.png)

## Typography

This project ships local OTF files from `font/termina-test/` and maps them to the `TerminalTest` family via `@font-face` in `src/index.css`.

Configured weights:

- `400` Regular
- `500` Medium
- `700` Bold
- `900` Black

The font is applied globally for body and display headings to preserve the terminal-inspired brand voice.

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Run development server

```bash
npm run dev
```

### 3. Build for production

```bash
npm run build
```

### 4. Preview production build locally

```bash
npm run preview
```

## Project Structure

```text
src/
  components/
  hooks/
  App.tsx
  index.css
assets/
font/
```

## Deployment

This app is optimized for static deployment (Vercel recommended).

## License

Add a license file if you intend to distribute or open-source this project.
