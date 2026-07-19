# rajeshkatuwal.github.io

Personal portfolio site for Rajesh Katuwal, published with GitHub Pages from the `docs/` folder.

## Overview

The site is a static portfolio with a WebGL fluid simulation background, a separate hero scene, and animated section reveals. The code has been split into a clean GitHub Pages structure so the repo can be deployed from `main` with `docs/` as the source.

## Features

- Single-page portfolio layout
- Hero section with intro copy and call-to-action buttons
- Skills, experience, education, projects, and contact sections
- Full-screen WebGL fluid simulation background on the non-hero portion of the page
- Responsive layout for desktop and mobile
- No build step required

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- WebGL
- Three.js for the page hero scene
- GSAP for scroll reveal animations

## Project Structure

- `docs/index.html` - GitHub Pages entry point
- `docs/style.css` - site styles
- `docs/script.js` - all page scripts and WebGL logic
- `README.md` - project documentation

## Local Preview

Open `docs/index.html` directly in a browser, or run a local server from the repo root:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/docs/`.

## Deployment

GitHub Pages is configured to deploy from the `main` branch and the `docs/` folder.

To update the live site:

1. Edit the files in `docs/`.
2. Commit your changes.
3. Push to `main`.
4. Wait for GitHub Pages to rebuild the site.

## Notes

- The site is intentionally framework-free and deploys as plain static assets.
- The fluid simulation and animation code live in `docs/script.js` so the GitHub Pages source folder stays clean.

## Credits

- Fluid simulation concept inspired by Pavel Dobryakov's WebGL Fluid Simulation.
