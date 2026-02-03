# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal portfolio website for Antonin Dvoracek (AnthonyDcodes) - a static single-page site hosted on GitHub Pages.

## Development

No build step required. Open `index.html` directly in a browser or use any local server:

```bash
open index.html                    # macOS - opens in default browser
python3 -m http.server 8000        # then visit localhost:8000
```

## Architecture

- **index.html** - Single-page structure with semantic sections (intro, experience, projects, achievements, contacts)
- **styles.css** - All styling including animations, responsive breakpoints (768px, 480px)
- **No JavaScript** - Pure HTML/CSS implementation

## Design System

- **Font**: Montserrat (Google Fonts)
- **Colors**: Dark background (#0A192F, #00343f, #000000 conic gradient), whitesmoke text, #64FFDA cyan accent
- **Animations**: Typing effect on intro text, staggered fade-in sections, loading bar at top, hover transitions on links/projects

## Deployment

Automatically deployed from `main` branch via GitHub Pages.
