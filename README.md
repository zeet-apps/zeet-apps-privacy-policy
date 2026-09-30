# Zeet Apps privacy policies

One GitHub Pages site for all Zeet Apps apps: https://zeet-apps.github.io/zeet-apps-privacy-policy/

Each app has its own folder and URL, which is what its App Store / Google Play listing links to:

| App | Page | Source of truth |
|---|---|---|
| Carnatic Vocal Practice | https://zeet-apps.github.io/zeet-apps-privacy-policy/carnatic-vocal-practice/ | `store/privacy/index.html` in the app repo; publish with `scripts/publish_privacy_policy.sh` |

To add an app: create `<app-slug>/index.html`, add a link to the root `index.html`, and point the
app's store listing at `https://zeet-apps.github.io/zeet-apps-privacy-policy/<app-slug>/`.

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `(root)`. `.nojekyll` keeps files
served as-is.
