# marty-russo.com

The source for my personal website. Plain HTML and CSS, no framework and no build
step — a single static page served by GitHub Pages, deployed automatically by a
GitHub Actions workflow on every push to `main`.

Kept intentionally minimal so it stays fast and easy to change.

## Layout

| Path | Purpose |
|------|---------|
| `index.html` | the page |
| `style.css` | styling |
| `CNAME` | custom domain (`marty-russo.com`) for GitHub Pages |
| `.github/workflows/deploy.yml` | builds and publishes to GitHub Pages |

## Local preview

Open `index.html` directly, or serve the folder with `python -m http.server` and
visit `http://localhost:8000`.
