# grob-lang.dev

Website for the [Grob programming language](https://grob-lang.dev).

## What this is

A single-page coming soon site. Self-contained HTML — no build step, no framework,
no dependencies beyond Google Fonts. Sparky is embedded as a base64 PNG.

## Structure

```
grob-lang.dev/
├── index.html                  ← the entire site
├── staticwebapp.config.json    ← Azure Static Web Apps routing and headers
└── README.md
```

## Deployment

This repo is connected to an Azure Static Web App. Every push to `main` deploys
automatically via the GitHub Actions workflow Azure created at setup.

The live site is at **https://grob-lang.dev**.

## Running locally

No build step needed. Open `index.html` directly in a browser, or serve it with
any static file server:

```powershell
# Python (if installed)
python -m http.server 8080

# Node (if installed)
npx serve .
```

## Before going live checklist

- [ ] Update GitHub URL — find `https://github.com` and replace with the actual repo URL
- [ ] Update contact email if `hello@grob-lang.dev` mailbox is not yet configured

## Licence

MIT — see the main [grob](https://github.com/grob-lang/grob) repo.
