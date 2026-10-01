# Salah time privacy policy

Public privacy page for **Salah time**, developed by **Inma**. This repository contains only the website and its hosting instructions. The Android app source and signing credentials are not included.

The approved app policy is maintained with the Android app. When that policy changes, update this page to match its wording and last-updated date. The website-hosting disclosure is separate from the app policy.

## Review and publish

Changes go through a feature-branch PR into `develop`, using squash merge. Only the `docs/` directory is intended for publication.

After the first PR is merged, enable **Settings → Pages → Deploy from a branch**, selecting **develop** and **/docs**, and enforce HTTPS. Subsequent merges into `develop` publish the reviewed page automatically. Hosting has not been enabled yet.

Expected public address: https://shaolinzaman-git.github.io/salah-time-privacy/

GitHub Pages logs visitors’ IP addresses for security purposes; the page links to GitHub’s privacy statement. It contains no scripts, analytics, external fonts or third-party images.

## Local preview

```sh
python3 -m http.server 8766 --bind 127.0.0.1 --directory docs
```

Open http://127.0.0.1:8766/. Serve only `docs/`, not another project directory.
