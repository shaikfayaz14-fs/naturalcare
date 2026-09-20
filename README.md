# Natural Care

A responsive static website for discovering skin and hair care products inspired by natural ingredients.

## Live website

Visit the deployed site: **[shaikfayaz14-fs.github.io/naturalcare](https://shaikfayaz14-fs.github.io/naturalcare/)**

## Features

- Responsive Natural Care landing page
- Skin and hair care product collection
- Product cards with prices and descriptions
- About, feedback, contact, and login pages
- Bootstrap carousel and Google Fonts integration
- GitHub Pages-compatible static HTML and CSS

## Pages

- [`index.html`](./index.html) — welcome page and entry point
- [`digital.html`](./digital.html) — product collection, about section, feedback, and contact form
- [`login.html`](./login.html) — sign-in form layout
- [`style.css`](./style.css) — shared styles

## Run locally

Because this is a static site, no build tools are required. Clone the repository and open `index.html` in a browser, or start a local server:

```bash
git clone https://github.com/shaikfayaz14-fs/naturalcare.git
cd naturalcare
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

The site is intended for GitHub Pages. In the repository settings, set **Pages → Build and deployment → Source** to **Deploy from a branch**, select the `main` branch and the `/ (root)` folder. After pushing changes, GitHub Pages may take a few minutes to publish the update.

## Note

The login, rating, and contact forms are currently presentation-only front-end forms. A backend service is required to store submissions or authenticate users.

## License

This project currently has no explicit license. Contact the repository owner before reusing it commercially.
