# spencersearle.github.io

Personal portfolio, plus the privacy and support pages for my apps.

Plain HTML and one stylesheet (`assets/site.css`). No build step. GitHub Pages serves the repo root.

## Pages

| Path | What |
|---|---|
| `/` | Home: work, about, contact |
| `/connect/privacy/` | Connect privacy policy (App Store Connect privacy URL) |
| `/connect/support/` | Connect support (App Store Connect support URL) |

New app? Add `/<app>/privacy/` and `/<app>/support/` by copying the Connect pages.

## Preview locally

```
python3 -m http.server 8000
```

then open http://localhost:8000. Paths are absolute (`/assets/...`), so opening the files directly from Finder will not load the styles.

Design and scope decisions are in `docs/spec.md`.
