# pablo.spa

A local workspace for rebuilding Pablo's personal site. The old site's content and images are preserved in `archive/original-site/` while a new publishing stack is chosen.

## Current files

- `index.html` and `styles.css`: an initial profile-page design exploration.
- `archive/original-site/`: original bilingual Markdown pages, blog posts, and uploaded images from the linked GitHub repository.

The current page is not connected to Netlify or another host. The archive preserves the source material; its dated “Now” content and untranslated Spanish post need review before reuse.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes the profile page from `index.html` and `styles.css` to GitHub Pages. It publishes the top-level site files and an optional `assets/` folder; the archived Hugo source stays out of the deployed site.
