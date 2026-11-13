# Onyx Web

Marketing site for [Onyx](https://github.com/reteshmani0-droid/Onyx) — a midnight-cherry agent
harness for your VM.

Static HTML/CSS. Deployed to GitHub Pages from `main`.

## Local preview

```bash
python3 -m http.server 8080
# or
npx serve .
```

## Publish

Push to `main`; the `pages.yml` workflow deploys automatically. Enable GitHub Pages
(Settings → Pages → Source: GitHub Actions) on first deploy.
