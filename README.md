# Paal KP's Personal Website

This repository now publishes a static website via GitHub Pages from the repository root.

## About

The website content is served from the root HTML pages and `assets/styles.css`.

## GitHub Pages Setup

- Source: `main` branch
- Publish directory: root
- `.nojekyll` is included to disable Jekyll processing and serve the static files directly.

## Local Preview

Open the HTML files directly in your browser to preview the site locally, or use a simple static server such as:

```bash
python3 -m http.server 8000
```

Then browse to `http://localhost:8000`.

## Notes

- The `site/` folder contains the generated static site source.
- Root files have been synced from `site/` so GitHub Pages can serve the site directly.

## License

This project is released into the public domain under the [Unlicense](LICENSE).