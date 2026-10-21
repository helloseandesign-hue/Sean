# LIU HAO — Portfolio

Personal design portfolio. Static HTML, CSS and JavaScript; no build step required.

## Preview locally

```sh
python3 -m http.server 8000 --directory site
```

## Publish

In repository Settings → Pages, select **GitHub Actions** as the source. Pushes to `main` deploy `site/` automatically.

Edit `site/index.html`, `site/style.css`, `site/app.js` and the project images in `site/assets/` to update the website.
