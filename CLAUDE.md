# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal portfolio website for Antonin Dvoracek (AnthonyDcodes) - a static single-page site hosted on GitHub Pages.

## Constraints

- **HTML/CSS only** - No JavaScript unless absolutely necessary. Keep it simple and lightweight.

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

- **Font**: JetBrains Mono (Google Fonts)
- **Colors**: Dark background (#0d1117), muted grey text (#8b949e), subtle green accent (#3fb950)
- **Style**: Minimal terminal aesthetic with blinking cursor, clean dividers, subtle hover effects

## Deployment

Automatically deployed from `main` branch via GitHub Pages.
