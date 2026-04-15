# Carousel Maker

A minimalist, browser-based editor for Instagram carousel posts — built for my own content workflow.

Single HTML file, no build step, no backend. Everything runs in the browser.

## Features

- **Three slide types**: photo cover, text-only, and CTA (3-line center layout)
- **Live global controls**: background color, text color, bullet-journal dot grid (toggle, color, opacity, size, spacing), handle
- **Per-slide controls**: text content, font sizes, alignment, order (italic above/below headline)
- **Photo backgrounds**: drop in any image for cover slides
- **Export**: download each slide as 1080 × 1350 PNG, or batch-download all
- **Persistence**: auto-saves to `localStorage`, plus export/import design as JSON
- **Typography**: Inter Black for punch lines, Apple Garamond italic for the soft ones (with serif fallbacks)

## Usage

Open `index.html` in a browser. Or use the hosted version via GitHub Pages.

## Stack

- Vanilla JavaScript — no framework, no build step
- [html2canvas](https://html2canvas.hertzen.com/) for PNG export (loaded from CDN)
- Google Fonts (Inter) + local Apple Garamond with fallback chain

## Roadmap

- [ ] IndexedDB for larger photo storage (localStorage caps around 5 MB)
- [ ] Drag-to-reorder slides
- [ ] Preset designs (starter templates)
- [ ] Undo / redo
- [ ] More slide layouts (split, quote, photo + text side-by-side)

## License

Personal project. MIT if you want to use it.
