# Lumix Tech — Qodex Website

Premium static website for Lumix Tech and Qodex, prepared for GitHub Pages and responsive use on desktop, tablet and mobile.

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
├── assets/
└── README.md
```

## GitHub Pages
1. Create a GitHub repository (for example, `lumixtech-website`).
2. Upload all files and folders from this project root.
3. In **Settings → Pages**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)`, then save.
5. GitHub Pages will publish the site; all page and asset links are relative, so they work from a project repository path as well as a custom domain.

## Local preview
Run `python -m http.server 5500` from the project root and open `http://localhost:5500/`.

## Notes
- No build step or framework is required.
- The design includes a mobile navigation menu and responsive layouts.
- Contact/support email: `support@lumixtech.in`.
