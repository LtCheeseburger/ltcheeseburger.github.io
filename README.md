# GitHub Pages Starter — xLtCheeseburger

A minimal, clean landing page you can deploy to GitHub Pages in minutes.

## Quick start

1. **Create the repo** (public):
   - Name it either `xLtCheeseburger.github.io` (user site) **or** any name you want (project site).
2. **Upload these files** to the repo root (`index.html`, `styles.css`, `assets/`).
3. **Enable Pages**: Settings → Pages → **Build and deployment** → Source: **Deploy from a branch** → Branch: `main` `/ (root)`.
4. Open the site URL shown in Settings → Pages.

> **Twitch embed:** In `index.html`, search for `parent=example.com` and replace with your actual domain (e.g., `xltcheeseburger.github.io`).

## Custom domain (optional)
- Add a `CNAME` file with your domain, and set DNS to GitHub Pages per docs.
- After DNS propagates, update the Twitch `parent` domain again.

## Personalize
- Edit the hero text, links, and project cards in `index.html`.
- Replace `assets/favicon.png` and `assets/og-cover.png` with your images (same filenames).
- Colors/spacing live in `styles.css` under `:root` tokens.

## SEO & Analytics
- Update `<title>` and meta description in `index.html`.
- Add analytics in `<head>` if you use them.

## Local preview
Open `index.html` in a browser. No build step required.

## License
MIT — feel free to reuse.
