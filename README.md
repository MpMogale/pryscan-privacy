# pryscan.com

The public site for the Pryscan iOS app. Three pages, served by GitHub
Pages:

- `/` — what the app is
- `/privacy/` — the privacy policy the App Store listing links to
- `/support/` — the support URL the App Store listing links to

Apple requires the last two and will not accept the same address for both.

This repository is public **only** so Pages can serve it; the app itself
lives in a private repository. `privacy/index.md` is a copy of `PRIVACY.md`
there — edit that one first, then bring the change here, so the policy the
app ships against and the policy the store links to cannot disagree.

`_layouts/default.html` and `assets/site.css` carry the app's palette, type
and mark, so every page looks like the product rather than a stock theme.
