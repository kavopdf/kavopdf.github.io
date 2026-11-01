# kavopdf.github.io

The KavoPDF website — live at **https://kavopdf.github.io/**

Everything is in `index.html` (HTML, CSS and JavaScript in one file), plus two images:
`app-icon.png` (the icon, also the favicon) and `og.png` (the social preview card).

## Updating the site
Edit `index.html`, commit to `main`, and GitHub Pages redeploys in about a minute.

## Publishing a new app version
The APK lives in a separate repo: **[kavopdf/app](https://github.com/kavopdf/app)**.
The download page reads that repo's latest release automatically, so the site always
serves the newest build — you never have to edit this repo for an app update.

1. Open https://github.com/kavopdf/app/releases → **Draft a new release**
2. Pick a new tag (e.g. `v1.1`) → **Create new tag**
3. Attach your APK. Any file name works - the page picks the first `.apk` asset -
   but `KavoPDF-<version>.apk` is what has been used so far.
4. Publish

> Fallback: if the GitHub API is unreachable (it allows 60 anonymous calls an hour),
> the button falls back to the releases page, and if you commit an APK to the root of
> *this* repo as `KavoPDF.apk` the button serves it directly instead.
