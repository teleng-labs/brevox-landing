# Brevox Landing

Static site for Brevox, a private iPhone and Apple Watch voice-first notebook.

Primary site: https://brevox-landing.vercel.app/

Transition mirror: https://teleng-labs.github.io/brevox-landing/

iOS + Apple Watch app repository: https://github.com/teleng-labs/brevox-ios

## Pages

- Home: `index.html`
- Privacy: `privacy/index.html`
- Support: `support/index.html`
- Terms: `terms/index.html`

## Deployment

Vercel is the primary host. Connect this repository to the `brevox-landing`
Vercel project so every push to `main` creates a production deployment.
`vercel.json` keeps clean URLs and the trailing-slash route shape in source
control.

GitHub Pages remains enabled during the App Store transition:

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
