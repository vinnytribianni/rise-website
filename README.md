# Rise — marketing website

Single-page marketing site for [Rise](https://github.com/vinnytribianni/riseapp), the iOS alarm app. Built as a static HTML page — no build step, no dependencies.

## Structure

- `index.html` — the whole site (styles and script are inline)
- `mascot/` — brand mascot art used on the page
- `phones/` — real app screenshots, framed for the site

## Running it locally

Just open `index.html` in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server 8080
```

## Deploying

Static hosting only (Vercel, Netlify, GitHub Pages, S3 — anything that serves plain files). No build command needed; the publish directory is the repo root.

One thing to update before this goes live: the "Download on the App Store" link in the download section currently points to a placeholder URL and needs the real App Store link once one exists.
