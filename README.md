# Ål Pizzeria, Restaurant & Cafè

A responsive sample restaurant website built with plain HTML, CSS, and JavaScript. No installation, build step, paid hosting, or API keys are needed.

## Deploy to GitHub Pages

1. Create a GitHub repository (public for GitHub Free).
2. Upload `index.html`, `styles.css`, `script.js`, `.nojekyll`, and the `.github/workflows/pages.yml` workflow, preserving the folder structure, to the `main` branch.
3. Open repository **Settings → Pages** and select **GitHub Actions** as the source.
4. Open **Actions → Deploy restaurant website to GitHub Pages → Run workflow**, selecting `main`. Future pushes to `main` deploy automatically.
5. When the workflow completes, open the deployment URL shown in the workflow or Settings → Pages. It usually has the form `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

Alternative without Actions: upload the four website files to the root of `main`, then choose **Settings → Pages → Deploy from a branch → main → / (root)**. Do not upload the workflow if using this alternative.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8080` in this folder and visit `http://localhost:8080`.

## Edit

- Content, links, restaurant details: `index.html`
- Colours, typography, responsive layout: `styles.css`
- Accessible mobile navigation: `script.js`

All local asset paths are relative, so repository subpaths on GitHub Pages work without additional configuration.

## Content notes

This is a sample concept, not an official site. Contact details, price range, and review excerpts come from the supplied listing. Opening hours and individual dish prices are deliberately not invented. Menu and Facebook buttons lead to the provided restaurant links. Food photography from Unsplash is illustrative; the location photo uses the supplied Google-hosted image. Remote images and Google Fonts require an internet connection and may change; system font fallbacks are supplied. Before official launch, confirm the details and replace illustrative photos with approved restaurant assets. No ordering or reservation backend is included.
