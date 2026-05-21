# NullDay Developer Site

Static site hosted via GitHub Pages at `https://jaimin-prajapati-ds.github.io/`.

Contains:
- `index.html` — landing page
- `privacy.html` — privacy policy (linked from Play Store)
- `app-ads.txt` — AdMob authorized seller declaration

## AdMob app-ads.txt

The `app-ads.txt` file authorizes Google AdMob (publisher ID `pub-7934704361744666`) to sell ads
for the NullDay app. After deploying via GitHub Pages, AdMob will crawl
`https://jaimin-prajapati-ds.github.io/app-ads.txt` within 24 to 48 hours and mark
the status as authorized in the AdMob dashboard.

## Deployment

This folder is meant to be pushed to a GitHub repository named
`jaimin-prajapati-ds.github.io` (a User Pages repo). GitHub Pages will then serve
the files at the root URL automatically.
