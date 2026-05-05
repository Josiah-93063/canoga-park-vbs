# Canoga Park SDA — Vacation Bible School 2026

Promotional landing page for the Canoga Park Community SDA Church Vacation Bible School (June 15–19, 2026).

## Live site

Once GitHub Pages finishes deploying, this site is available at:

**https://josiah-93063.github.io/canoga-park-vbs/**

## Project structure

```
.
├── index.html        # Single-page promo site
├── assets/
│   └── flyer.jpg     # Printable flyer image (referenced from index.html)
└── README.md
```

## Updating content

- **Edit the page:** modify `index.html` and commit to `main`. GitHub Pages will redeploy automatically (usually within ~1 minute).
- **Add the flyer image:** upload your flyer as `assets/flyer.jpg`. The site already references this path.
- **Add the registration form / QR code:** in `index.html`, find the section with `id="register"` and replace the Instagram link with your final Google Forms URL. To embed a QR code, drop a PNG in `assets/qr.png` and reference it with `<img src="./assets/qr.png" alt="Registration QR code" />`.

## Local preview

Open `index.html` directly in a browser, or run a quick local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosting: GitHub Pages, served from the `main` branch root. No build step required.
