# Brevox Landing

Static GitHub Pages site for Brevox, a private iPhone and Apple Watch voice-first notebook.

Live site: https://teleng-labs.github.io/brevox-landing/

## Pages

- Home: `index.html`
- Privacy: `privacy/index.html`
- Support: `support/index.html`
- Terms: `terms/index.html`

## Deploy on GitHub Pages

1. Create a GitHub repository, for example `brevox-landing`.
2. Push this folder as the repository root.
3. In GitHub, open Settings -> Pages.
4. Set source to `Deploy from a branch`.
5. Select `main` and `/root`.

The `.nojekyll` file keeps GitHub Pages from running Jekyll.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
