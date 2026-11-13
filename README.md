# Cyrine Karray — Portfolio

Static website reproducing the nine pages of the supplied presentation in order, with a scroll reveal animation. Page images preserve the PDF layout; reduced-motion preferences are respected.

## Files

- `index.html`: the nine presentation pages and accessible text.
- `pages/`: page images rendered from the PDF.
- `style.css`: responsive sizing and animation styles.
- `script.js`: scroll reveal behavior.
- `vercel.json`: deployment headers.

## Preview

Run `python3 -m http.server 3000` in this directory, then open http://localhost:3000.

## Deployment

This is a static site with no dependencies or build command. Serve the repository root.

For GitHub Pages, publish the `main` branch from `/ (root)`. The `.nojekyll` file preserves the static files without Jekyll processing. All page asset paths are relative, so they also work on a repository Pages URL.

Live portfolio: https://idross.github.io/cyrine-karray-portfolio/

The website contains personal portfolio content and contact information supplied for publication. No domain account credentials are included.
