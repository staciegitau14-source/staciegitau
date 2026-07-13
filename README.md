# Physical Atlas of Africa

A polished, browser-friendly atlas of Africa that brings together country profiles, regional summaries, terrain and climate notes, elevation highlights, and an interactive map overlay.

## Features

- Explore all African countries through an interactive map
- Review country profiles with capital, area, coastline, highest point, rivers, terrain, climate, and resources
- Filter by region and view regional overviews
- Browse an elevation chart for major peaks
- Works as a static site and can be hosted on GitHub Pages

## Project structure

- [docs/index.html](docs/index.html) — landing page for the published site
- [docs/afrrika%20karte.html](docs/afrrika%20karte.html) — main atlas page
- [docs/favicon.svg](docs/favicon.svg) — site icon
- [docs/site.webmanifest](docs/site.webmanifest) — web app manifest
- [.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml) — GitHub Pages deployment workflow

## Local preview

You can preview the site locally by opening [docs/index.html](docs/index.html) in a browser, or by serving the repository with a simple web server such as:

```bash
python -m http.server 8000
```

Then open http://127.0.0.1:8000/.

## Deployment

The site is configured for GitHub Pages. Push the repository to GitHub and enable Pages with the GitHub Actions source.
