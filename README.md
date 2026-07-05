# Sepideh Raei — Personal Academic Website

Static HTML replica of [sepidehraei.weebly.com](https://sepidehraei.weebly.com/), rebuilt for GitHub Pages.

## Structure

- `index.html` — Home (bio, photo, contact)
- `research.html` — Publications, working papers, work in progress
- `teaching.html` — Awards and teaching history
- `cv.html` — CV download button
- `css/style.css` — Site-wide stylesheet (replicates the Weebly theme look)
- `images/` — Profile photo and background image
- `files/` — Paper PDFs and CV

## Publish with GitHub Pages

1. Push this repo to GitHub.
2. On GitHub: **Settings → Pages → Source: Deploy from a branch**, select `main` and `/ (root)`.
3. The site will be live at `https://sepidehraei.github.io/sepidehraei/` (or rename the repo to `sepidehraei.github.io` to serve it at `https://sepidehraei.github.io/`).

## Local preview

Any static server works, e.g.:

```sh
python3 -m http.server 8080
```

then open <http://localhost:8080>.
