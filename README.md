# MyShot — public site

The pages Google requires for OAuth Production status, and the project's public face.

| File | Purpose |
|---|---|
| `index.html` | Homepage — the "Application home page" URL |
| `privacy.html` | Privacy policy — the "Application privacy policy" URL |
| `terms.html` | Terms of service |
| `style.css` | Shared styling, light and dark |

## Why this is a separate repository

The main MyShot repository is private, and GitHub Pages only serves public
repositories on the free plan. Keeping the site separate means publishing these
pages does not expose the application source.

## Publishing

1. Create a **public** repository named `myshot-site`
2. Upload the contents of this directory to its root
3. Settings → Pages → Source: `main`, folder `/ (root)`
4. Wait ~1 minute, then the pages are live

## Keeping it accurate

> [!IMPORTANT]
> The privacy policy describes what the application actually does. If MyShot's
> data handling changes — server-side accounts, telemetry, a new third-party
> processor — **update this policy before that release ships**, not after.
> Sprint 9 in the main repository revises it for the v2 backend.
