# Yantra — company site

Served at <https://yantraco.github.io/site/>. Carries the company's public face and the
pages Google requires for MyShot's OAuth Production status.

| File | Purpose |
|---|---|
| `index.html` | Company homepage — the "Application home page" URL |
| `myshot.html` | MyShot product page |
| `privacy.html` | Privacy policy — the "Application privacy policy" URL |
| `terms.html` | Terms of service |
| `style.css` | Shared styling — night palette, per-product accents |

## Why this is a separate repository

The MyShot application repository is private, and GitHub Pages only serves public
repositories on the free plan. Keeping the site separate means publishing these
pages does not expose the application source.

## Publishing

1. Settings → Pages → Source: `main`, folder `/ (root)`
2. Push to `main`; the pages are live ~1 minute later

## Keeping it accurate

> [!IMPORTANT]
> The privacy policy describes what the application actually does. If MyShot's
> data handling changes — server-side accounts, telemetry, a new third-party
> processor — **update this policy before that release ships**, not after.
> Sprint 9 in the main repository revises it for the v2 backend.


