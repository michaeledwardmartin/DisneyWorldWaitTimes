# Disney World Wait Times

A personal, static HTML/CSS/JavaScript dashboard using the free ThemeParks.wiki API.

## Use
Open `index.html` in a browser. If local file browser restrictions block requests, run `python -m http.server 8000` in this folder and open `http://localhost:8000`.

## GitHub Pages
Create a GitHub repository, upload `index.html`, `style.css`, and `app.js` to its root, then go to Settings → Pages → Deploy from a branch → main → /(root) → Save. The site will be available at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`.

## Features
Four-park overview and individual views; 2-minute refresh; search; sorting; favorites saved on this device; operating-only filter; responsive layout; status and color-coded standby times.

## Notes
Data comes from ThemeParks.wiki, not Disney directly. The dashboard does not display missing attractions as closed. It requires an internet connection, and third-party API access may occasionally fail. Attribution is included as required by the provider.
