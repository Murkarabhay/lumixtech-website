# Lumix Tech — Qodex Website

Premium static website for Lumix Tech and Qodex, prepared for GitHub Pages, a custom domain, desktop, tablet and mobile.

## Pages
- `index.html` — Lumix Tech homepage
- `qodex.html` — Qodex product page
- `qodex-privacy.html` — Qodex Privacy Policy
- `qodex-support.html` — Qodex Help & Support

## Project structure
```text
.
├── index.html
├── qodex.html
├── qodex-privacy.html
├── qodex-support.html
├── style.css
├── script.js
├── .nojekyll
├── .gitignore
└── assets/
    ├── lumix-logo.png
    ├── qodex-logo.png
    ├── qodex-phone-qr.png
    ├── qodex-phone-barcode.png
    └── qodex-phone-barcode.svg
```

## GitHub Pages upload
Upload **everything inside this ZIP**, including the complete `assets` folder. Do not upload only the HTML files.

For GitHub Pages:
1. Open your repository.
2. Upload all project files and the `assets` folder to the repository root.
3. Commit the changes.
4. Go to **Settings → Pages**.
5. Choose **Deploy from a branch**, select `main`, and select `/ (root)`.
6. Save and wait for GitHub Pages to redeploy.

All website asset paths are relative (`assets/...`), so they work on a custom domain and on a GitHub Pages project path.

## Local preview
Run `python -m http.server 5500` from the project root and open `http://localhost:5500/`.

## Final updates
- Lumix logo asset is transparent/rounded so no white rectangular backing appears on the dark site.
- Qodex QR preview is packaged locally and displayed crisply.
- Barcode preview has a PNG copy for reliable static hosting.
- Qodex app count is `1`.
- Support/contact email is `support@lumixtech.in`.
- Qodex title `Q` uses the Qodex blue brand color.
- Homepage app card remains compact and left-aligned.
- Responsive/mobile layout is retained.
