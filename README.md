# Instagram Login Mockup

A small static mockup that recreates an Instagram-style login page and phone mockups for presentation or prototyping.

## Files

- `Insta.html` — The main HTML file with embedded CSS and JavaScript. It contains a responsive two-column layout (visual phone mockups on the left, login form on the right), animations, and interactive UI touches (input focus, simple login button behavior).

## Features

- Instagram-inspired login UI with dark theme.
- Phone mockups with layered frames, story bubbles, posts, and floating icons.
- Responsive behavior: the left-side visual is hidden on small screens for easier viewing of the login form.
- Small interactive scripts:
  - Input focus/blur styling
  - Shake animation for empty required fields
  - Button hover scaling and a simple "Logging in..." state
- Self-contained: no external build tools required; fonts loaded from Google Fonts.

## Preview

Open `Insta.html` in your browser to view the mockup. On desktop viewports you'll see the left visual panel with phone mockups and the right login panel. Resize the browser to see responsive behavior.

## How to use

1. Clone the repository:

   git clone https://github.com/Moshtly/location-.git
2. Open `Insta.html` in your browser (double-click the file or use "Open with...").

This is a static file—no server or build step is required.

## Development notes

- The UI is implemented with pure HTML, CSS, and a small amount of vanilla JavaScript at the bottom of the file.
- If you want to extract styles into a separate CSS file or split JavaScript into a module, move the `<style>` and `<script>` content out of `Insta.html` and update the HTML references.
- A couple of SVG path elements in the file show truncated data (indicated with `[...]`). Replace those with full SVG paths if you plan to use the icons in production.

## Contributing

Contributions are welcome. Open an issue or submit a pull request with focused changes and include before/after screenshots for visual adjustments.

## License

This project has no license file yet. If you want, I can add an MIT or other license for you.

## Author

Created by Moshtly.
