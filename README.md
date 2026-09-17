# Nickos C. Armijo — Developer Portfolio

Personal portfolio site. Static HTML, CSS and JavaScript — no framework, no build step,
no dependencies. One file plus assets.

**Live:** _(add your URL here after deploying)_

## Stack

Hand-written HTML5, CSS (custom properties, grid, flexbox) and vanilla JavaScript.
Inline SVG icon set drawn on a 24px grid. Google Fonts (Inter, JetBrains Mono).

## Structure

```
index.html                        the entire site — markup, styles and scripts
assets/profile.jpg                profile photo
assets/og.png                     social link-preview card
assets/nickos-armijo-resume.pdf   resume, linked from the hero
robots.txt
```

## Running locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Notes

- Responsive from 390px up; tested at phone and desktop widths.
- Motion and pointer effects respect `prefers-reduced-motion` and are skipped on touch devices.
- Theme colors are CSS custom properties on `:root` in `index.html`.
