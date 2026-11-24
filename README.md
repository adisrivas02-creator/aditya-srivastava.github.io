# Aditya Srivastava — Academic Website

A minimal, static academic website designed for GitHub Pages.

## Publish on GitHub Pages

1. Create/sign in to a GitHub account.
2. Create a **public** repository named exactly `YOUR_GITHUB_USERNAME.github.io`.
3. Upload the contents of this folder (not the outer ZIP file).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site at `https://YOUR_GITHUB_USERNAME.github.io`.

## Before publishing

- Replace the placeholder thesis PDF notes in `index.html` with links once you add the two thesis PDFs to `papers/`.
- Add only FDL policy outputs or research material that you are authorised to share publicly.
- Review the CV PDF in `assets/` and replace it whenever you update your CV.
- Check the employment dates and descriptions carefully before making the site public.
- If you prefer not to publish your email address, remove or obfuscate the email links.

## Suggested file layout

```text
.
├── index.html
├── README.md
├── assets/
│   └── Aditya_Srivastava_CV.pdf
└── papers/
    └── (add thesis PDFs and approved research abstracts here)
```

The website uses no build tools or external JavaScript libraries. Google Fonts are loaded remotely; the page remains readable with system fonts if they are unavailable.
