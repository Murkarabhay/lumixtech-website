# Lumix Tech — GitHub Pages clean-URL package

## Folder structure
- `index.html` — homepage (`https://lumixtech.in/`)
- `qodex/index.html` — Qodex (`https://lumixtech.in/qodex`)
- `privacy/index.html` — Privacy Policy (`https://lumixtech.in/privacy`)
- `terms/index.html` — Terms (`https://lumixtech.in/terms`)
- `delete-account/index.html` — Account deletion (`https://lumixtech.in/delete-account`)

## Deploy
1. Extract this ZIP.
2. Open the existing GitHub repository used by GitHub Pages.
3. Back up the current site before replacing files.
4. Upload the root `index.html` and the four folders (`qodex`, `privacy`, `terms`, `delete-account`) into the same publishing folder (usually repository root).
5. Keep the existing `CNAME` file and any other assets/configuration needed by the site.
6. Commit to the same publishing branch and wait for GitHub Pages deployment.
7. Test all five URLs.

GitHub Pages serves each folder's `index.html` at its folder path, so visitors do not see `.html` in the URL. The host may normalize folder URLs with a trailing slash.
Do not change DNS or GitHub Pages settings for this content update.
