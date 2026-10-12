# Foster Engineering Website

Static website (HTML / CSS / JS) — no build step required.

## Structure

```
index.html          # markup
css/style.css       # styles
js/main.js          # all scripts (i18n EN/TH, projects, canvas effects)
assets/
  images/           # logo, hero, features, services, projects, clients
  video/            # page header videos (webm + mp4)
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deploy on GitHub Pages

Settings → Pages → Deploy from branch → `main` / root.
