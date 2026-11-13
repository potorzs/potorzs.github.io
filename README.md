# potorzs.github.io (root site)

Only for Carmeo password saving (1.2.0): the phone links the app to this domain via files that must sit in the
domain root, not under /carmeo.

- `.well-known/apple-app-site-association` – iOS Passwords (Associated Domains `webcredentials:potorzs.github.io`)
- `.well-known/assetlinks.json` – Android Digital Asset Links (Google Password Manager)
- `.nojekyll` – otherwise GitHub Pages skips folders starting with a dot
- `index.html` – forwards to /carmeo/
