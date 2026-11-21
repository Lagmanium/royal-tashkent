# Tashkent Heritage — static website

A small, multilingual static website about the historical landmarks and architecture of Tashkent. Built from plain HTML, CSS and JavaScript; no build step, framework, server, database or search service is required.

## Pages

- `index.html` — main page and project overview (no search bar)
- `landmarks.html` — landmark catalogue with category filters and expandable details
- `districts.html` — historic urban areas
- `architecture.html` — architectural features and visual language
- `sources.html` — research sources and image attributions

## Local preview

Open `index.html` in a browser. For a more consistent local preview, run a simple static server from this folder, for example `python -m http.server 8000`, then open `http://localhost:8000`.

## GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder (not the folder wrapper) to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`.
4. Save. GitHub Pages will publish `index.html` as the home page.

## Images and attribution

This site hotlinks photographs from Wikimedia Commons and the Tashkent City Administration portal. An internet connection is required for the photographs to load. Image authors and licences are listed in the Sources page. If you want a fully self-contained repository, download/reuse the images according to their licence terms, place them in `assets/images/`, and update the image URLs at the top of `js/site.js`.

## Editing content

Main content, translations (RU / UZ / EN), external source links and image URLs are in `js/site.js`. Shared visual styles are in `css/site.css`.
