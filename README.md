# PawsHome — Animal Shelter Website

A static HTML/CSS/JavaScript website published with GitHub Pages.

## Pages
- `index.html` — Home
- `adopt.html` — Browse pets
- `buddy.html`, `luna.html`, `max.html`, `snowball.html` — Pet profiles
- `adoption-application.html` — Adoption application
- `contact.html` — Contact page

## Run locally
Open `index.html` in a browser, or use the VS Code Live Server extension.

## Publish on GitHub Pages
The repository uses the workflow in `.github/workflows/pages.yml` to publish the site from the `main` branch. In the repository settings, choose **Settings → Pages → Build and deployment → Source → GitHub Actions**. New commits to `main` trigger deployment automatically.

## Important notes
- The original upload did not include the five referenced pet photographs. The `images/` folder contains simple SVG placeholders. Replace them with the real photographs when available.
- The contact and adoption forms currently validate fields in the browser only. They do **not** send or store submissions because no backend service was provided.
- Do not commit passwords, API keys, or `.env` files.
