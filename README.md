# Northhouse Securities

Official marketing website for **Northhouse Securities** — a cybersecurity consultancy and managed security services firm launching October 2026 in London, with an Accra office following in January 2027.

🔗 Live site: _add your GitHub Pages link here once deployed_

## What's inside

```
├── index.html      # Page structure and content
├── styles.css      # All styling (design tokens, layout, responsive rules)
├── script.js       # Mobile navigation menu behavior
├── assets/
│   └── logo.png    # Northhouse Securities shield logo
└── README.md
```

## Sections

- **Hero** — mission statement and launch announcement
- **About** — company mission and quick facts
- **Services** — the six core security disciplines offered
- **Locations** — office launch timeline (City of London, East London, Accra)
- **Contact** — values and a way to get in touch

## Running locally

No build step required — it's plain HTML/CSS/JS. Just open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This site is built to deploy directly on **GitHub Pages** — no build tools needed. See the deployment guide for step-by-step instructions.

## Editing content

- **Contact email**: search `styles.css`-adjacent `index.html` for `mailto:` and replace `hello@northhousesecurities.com` with your real address.
- **Colors**: all defined as CSS variables at the top of `styles.css` under `:root`.
- **Copy**: all text lives directly in `index.html`.
