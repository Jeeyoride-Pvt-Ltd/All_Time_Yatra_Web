# All Time Yatra Web

Marketing website for All Time Yatra, built with React, Vite, Tailwind CSS v4, Framer Motion, and Lucide icons.

## Overview

This project is a single-page landing site for the All Time Yatra ride-sharing platform. It includes:

- Hero section with product positioning and store CTA messaging
- About, process, features, gallery, comparison, contact, and footer sections
- Smooth section scrolling navigation
- Motion-based entrance and hover animations
- Static asset delivery through the Vite `public/` directory

## Tech Stack

- React 19
- Vite 8
- Tailwind CSS 4
- Framer Motion
- Lucide React
- React Scroll

## Project Structure

```text
src/
  components/
    About.jsx
    Contact.jsx
    Features.jsx
    Footer.jsx
    Gallery.jsx
    Hero.jsx
    HowItWorks.jsx
    Navbar.jsx
    WhyChooseUs.jsx
  App.jsx
  index.css
  main.jsx
public/
  logo.png
  hero1.jpeg
  about_1.png
  about_2.png
  gallary1.jpeg ... gallary6.jpeg
```

## Local Development

Install dependencies:

```bash
npm install
```

Start the dev server:

```bash
npm run dev
```

Open the local URL shown in the terminal.

## Production Build

Create the production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Deployment Notes

- The production output is generated in `dist/`.
- Static images are served from `public/` using root-relative paths like `/logo.png`.
- If deploying under a subpath instead of a root domain, update the Vite base config before release.

## Content Notes

- Footer company/legal/support links are currently placeholder links.
- Store CTA buttons currently present launch messaging and may need real store URLs when available.
- Contact email is `alltimeyatrapvtltd@gmail.com`.
