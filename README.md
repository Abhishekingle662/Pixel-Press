# Pixel-Press
This is a client-side offline image compressor.

## GitHub Pages deployment

This repository is configured to deploy to GitHub Pages using GitHub Actions.

- Workflow file: `.github/workflows/deploy-pages.yml`
- Trigger: push to `main` (and manual `workflow_dispatch`)
- Deployment target: GitHub Pages

### One-time setup in GitHub

1. Open **Settings → Pages** in this repository.
2. Set **Source** to **GitHub Actions**.
3. Push to `main` and wait for the **Deploy to GitHub Pages** workflow to finish.
