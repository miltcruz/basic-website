# Basic Website

A minimal static website template with a few example pages and assets. This repository contains a simple multi-section homepage, an about page, a contact page, basic styles, and a small image asset directory — suitable for learning, demos, or quick prototypes.

## Features

- Simple, semantic HTML structure (`index.html`, `about.html`, `contact.html`).
- External CSS in `style.css` and JavaScript in `script.js`.
- Local image assets stored under `assets/img/`.
- Responsive-friendly meta viewport and a basic navigation menu.

## File Structure

```
basic-website/
├─ index.html         # Homepage
├─ about.html         # About page
├─ contact.html       # Contact page
├─ style.css          # Stylesheet
├─ script.js          # Small JS for interactions
└─ assets/
   └─ img/            # Image files used by the site
```

## Getting Started

- Option A — Open locally: open `index.html` in your browser (double-click or use your editor's "Open in Browser").
- Option B — Use a simple local server (recommended for testing relative paths and fetches):

  - Using Python 3:

    ```bash
    python -m http.server 8000
    # then open http://localhost:8000 in your browser
    ```

  - Using Node (http-server):

    ```bash
    npm install -g http-server
    http-server -p 8000
    ```

## Development Notes

- Edit HTML files directly and refresh the browser to view changes.
- Keep images inside `assets/img/` and reference them relatively (e.g., `assets/img/photo.jpg`).
- The project uses a Google Fonts import in `index.html` — an internet connection is required to load that font.

## Contributing

If you'd like to extend this project:

- Create a branch for your changes.
- Improve styles, add accessibility features, or add a build step (e.g., SCSS, bundler).
- Open a pull request with a clear description of changes.

## License

This repository does not include a license file. If you want to share or publish this project, consider adding a license such as the MIT License.

----

Created for a simple static website demo.
