# Arham Naeem: Portfolio

Personal portfolio site. A single static page (`index.html`) with no build step and no dependencies apart from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

- **GitHub Pages:** go to the repo's Settings → Pages, set Source to "Deploy from a branch" and choose `main` / root. The site goes live at `https://<username>.github.io/<repo>/`.
- **Vercel / Netlify:** import the repo. No build command is needed; set the output directory to the root.

## Adding project links

Each project card in `index.html` has `data-demo` and `data-code` attributes. Put a URL in either one and a "Live demo →" or "Code →" button appears on that card automatically.
