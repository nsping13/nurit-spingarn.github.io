# Nurit Spingarn — personal academic website

A responsive, static academic website designed for GitHub Pages. It uses plain HTML, CSS, and a small JavaScript file; no build step is required.

## Preview locally

Open `index.html` in a browser, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository named `YOUR-USERNAME.github.io` (replace with your GitHub username).
2. Upload the contents of this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Your site will be published at `https://YOUR-USERNAME.github.io/`.

## Before publishing

Search the files for `TODO` and `YOUR_` and update:
- Google Scholar, GitHub, and LinkedIn URLs in `index.html`.
- Your email address.
- Your CV PDF: add it as `assets/nurit-spingarn-cv.pdf`.
- The code / paper / project-page links and complete publication metadata.
- Confirm author lists, publication years, venues, and titles.
- Replace the abstract hero artwork with a portrait or research image if desired.

## Customize

- Main content and links: `index.html`
- Colors, layout, typography, responsive behavior: `styles.css`
- Mobile navigation and footer year: `script.js`

The website is intentionally dependency-light. Google Fonts are loaded remotely; system fallbacks are provided.
