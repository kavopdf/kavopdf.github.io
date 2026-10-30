# kavopdf.github.io

The KavoPDF website — live at **https://kavopdf.github.io/**

Everything is in `index.html` (HTML, CSS and JavaScript in one file), plus the app
icon and one screenshot.

## Updating the site
Edit `index.html`, commit to `main`, and GitHub Pages redeploys in about a minute.

## Publishing a new app version
The APK lives in a separate repo: **[kavopdf/app](https://github.com/kavopdf/app)**.
The download page reads that repo's latest release automatically, so the site always
serves the newest build — you never have to edit this repo for an app update.

1. Open https://github.com/kavopdf/app/releases → **Draft a new release**
2. Pick a new tag (e.g. `v1.1`) → **Create new tag**
3. Attach your APK and rename the asset exactly **`KavoPDF.apk`**
4. Publish

> Fallback: if you'd rather skip releases, commit the APK to the root of *this*
> repo as `KavoPDF.apk` and the download button will serve it directly.
