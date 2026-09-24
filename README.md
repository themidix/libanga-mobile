# Libanga Mobile Demo

Static, self-contained prototype of the Libanga Talent mobile app. Everything (React, fonts, images) is bundled inside `index.html`, so there is no build step and no external dependency.

## Run locally

    python3 -m http.server 8000   # then open http://localhost:8000

## Deploy (GitHub Pages)

Repo Settings → Pages → Source: **Deploy from a branch** → `main` / `(root)`.
The site is served at `https://<user>.github.io/<repo>/`.
