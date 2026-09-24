# Hemant Poonia — Personal Research Website (v1)

Static GitHub Pages site for Hemant Poonia, AI Research Scientist at IIT Gandhinagar.

## Local preview

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on GitHub Pages

1. Create a repository named `Drought-JohnDoe.github.io` under the `Drought-JohnDoe` account.
2. Copy all files in this folder to the repository root.
3. Push to the `main` branch.
4. In **Settings → Pages**, choose **Deploy from a branch**, `main`, `/ (root)` if Pages is not already enabled automatically.
5. The site will be available at `https://drought-johndoe.github.io/`.

## Main files

- `index.html` — page content
- `styles.css` — visual system and responsive layout
- `script.js` — navigation + reveal animations
- `assets/` — portrait, convocation images, CV, favicon

## Next iteration ideas

- Add publication thumbnails/figures and project detail pages.
- Add a dedicated media page with all verified coverage.
- Add a talks/presentations section.
- Add a lightweight publications data file so new papers are easier to update.
- Add a custom domain if desired.
