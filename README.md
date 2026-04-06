# Ruben Munoz — Portfolio

## Files
- `index.html` — Main portfolio page (hero, skills, certs, projects)
- `contact.html` — Contact page
- `style.css` — Shared styles
- `profile.jpg` — Your profile photo

## Adding Project Screenshots

Open `index.html` and find the `projects` array near the bottom of the file.
Each project has an `images: []` array. Add your screenshot file paths there:

```js
images: ['images/soc-lab-dashboard.jpg', 'images/soc-lab-alerts.jpg']
```

Put your screenshots in an `images/` folder next to `index.html`.
The lightbox will let visitors click through all of them.

## Deploy to GitHub Pages
Push all files to your `rubenmunoz7.github.io` repo (or keep in a branch).
No build step needed — it's plain HTML/CSS/JS.
