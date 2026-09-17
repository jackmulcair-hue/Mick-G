# Mick-G

Static PWA for GitHub Pages.

## Deploy

The `Deploy static site to GitHub Pages` workflow builds and deploys the repository on every push to `main`.

In the repository settings, set **Pages > Build and deployment > Source** to **GitHub Actions**. After that, the workflow publishes `index.html`, `manifest.webmanifest`, and the `icons` directory automatically.