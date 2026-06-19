# basementheroes.net

Personal site for **Grant Arundell** — lead game programmer, designer, and team leader.
A single static page served via GitHub Pages at [basementheroes.net](https://basementheroes.net).

## Stack

Hand-written HTML / CSS / vanilla JS — no build step, no framework.

| File | Purpose |
|---|---|
| `index.html` | The page (all content/sections) |
| `styles.css` | Styling |
| `main.js` | Mobile nav toggle + footer year |
| `CNAME` | Custom domain for GitHub Pages |

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

Pushing to `main` publishes automatically via GitHub Pages. The custom domain is
set in **Settings → Pages**; DNS is managed at the domain registrar.
