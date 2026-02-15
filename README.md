# amantech.dev

Landing site for the Amantech app. Static HTML/CSS, ready to host on any provider (e.g. GitHub Pages, Netlify, Vercel, or your new host after moving from GoDaddy).

## What’s included

- **index.html** – Landing page with hero, download buttons (App Store / Google Play), and a short features section
- **privacy.html** – Privacy policy page
- **css/styles.css** – Shared styles and color variables so you can match your app’s branding

## Customize

1. **Colors** – Edit the `:root` variables in `css/styles.css` (e.g. `--color-primary`, `--color-bg`, `--color-accent`) to match your app.
2. **Copy** – Update the hero headline and tagline in `index.html`, and adjust the feature cards if needed.
3. **Download links** – Replace the `href="#"` on the App Store and Google Play buttons with your real store URLs.
4. **Privacy** – Update the contact email in `privacy.html` (replace `privacy@amantech.dev` with your address) and tweak the policy text to match your app.

## Run locally

Open `index.html` in a browser, or use a simple server:

```bash
# Python
python3 -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Deploy

- **GitHub Pages**: Push to a repo, enable Pages in Settings → Pages, and set source to main branch (root or `/docs` if you put the files in `docs/`).
- **Netlify / Vercel**: Connect the repo and use the project root as the publish directory (no build step).
- **GoDaddy / FTP**: Upload the contents of this folder to your web root so `index.html` and `privacy.html` are at the root and `css/styles.css` is in a `css/` folder.
