# flutterwave

A small, static frontend project showcasing core HTML and CSS concepts: navigation, lists, layout techniques (Flexbox, Grid, Columns), positioning, utility classes, animations, transforms, and simple responsive design. The project contains multiple demo pages that you can open directly in a browser or serve via a lightweight local server.

## Features

- **Multiple demo pages**: `index.html`, `one.html`, `two.html`
- **Typography**: Google Fonts (Roboto)
- **Navigation and lists**: basic nav bars and list styling
- **Layout techniques**:
  - Flexbox (active in `two.css`)
  - Grid (illustrative examples commented in `two.css`)
  - Multi-column layout (in `index.css`)
- **Positioning**: absolute, relative, fixed, sticky (examples in `two.css`)
- **Animations & transforms**: keyframe animation, rotate, skew, transitions (in `one.css`)
- **Card UI**: simple profile cards with images (in `two.html`)
- **Responsive touches**: media query example in `two.css`

## Project structure

```
/home/ochuko/Desktop/projects/flutterwave/
├─ index.html
├─ index.css
├─ one.html
├─ one.css
├─ two.html
├─ two.css
├─ flutter wave.png
├─ yang-deng-jxebHgzy_SM-unsplash.jpg
├─ li-shanting-AGy0SxTzqr8-unsplash.jpg
├─ project.html (empty placeholder)
├─ project.css  (empty placeholder)
└─ README.md
```

## Quick start

You can open any of the HTML files directly in your browser. For best results (especially for relative paths and future extensions), use a simple local server.

- Option A: Python (built-in)

  ```bash
  cd /home/ochuko/Desktop/projects/flutterwave
  python3 -m http.server 5500
  ```

  Then visit `http://localhost:5500/index.html`.

- Option B: VS Code Live Server
  - Open the folder in VS Code
  - Install the “Live Server” extension
  - Right-click `index.html` → “Open with Live Server”

## Pages

- **index.html**: Playground of list styles and a columns demo (HTML sections are largely commented in/out for experimentation).
- **one.html**: Utility classes, simple nav, and animated squares showing transitions, transforms, and keyframes (see `.animate` and `@keyframes sly` in `one.css`).
- **two.html**: Header + nav + card-style profiles; layout and responsive styling in `two.css`. Contains commented examples for positioning, Flexbox, Grid, and a “hero” image caption section.

## Technologies

- **HTML5** and **CSS3** only (no build step)
- **Google Fonts**: Roboto

## Notes

- Several blocks in the HTML and CSS are intentionally commented to serve as learning snippets. Uncomment sections as needed while experimenting.
- Image assets are included for the card and hero examples.

## Contributing

Feel free to open issues or submit edits that add small, focused demos (e.g., forms, CSS variables, accessibility examples). Keep the project dependency-free and easy to run.

## License

No license specified. If you plan to use or share, consider adding a license (e.g., MIT).
