# Yarima Electricals

Yarima Electricals is a React single-page application built with Create React App.

## Local development

Requirements: Node.js 20 and npm.

```sh
npm ci
npm start
```

## Production build

```sh
npm run build
```

The optimized static site is written to `build/`.

## GitHub Pages deployment

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys
the app whenever changes are pushed to `main` or `master`. In the repository's
**Settings > Pages**, choose **GitHub Actions** as the build and deployment
source. The workflow configures the repository base path and a fallback page
for client-side routes.
