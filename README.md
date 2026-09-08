# Marty Russo — website

A minimal static website. Plain HTML + CSS, no build step.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The page. Currently just shows "Marty Russo" at the top. |
| `style.css` | Styling. |
| `.github/workflows/deploy.yml` | Publishes the site to GitHub Pages on every push to `main`. |

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server
```

Then visit http://localhost:8000

## Publish

1. Create a repo on GitHub and push this folder to the `main` branch.
2. In the repo: **Settings → Pages → Build and deployment → Source = GitHub Actions**.
3. Every push to `main` deploys automatically. The live URL appears in the
   Actions run summary and under Settings → Pages.

## Add content

Put it inside the `<main>` element in `index.html`.
