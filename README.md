# FirstStep MVP

A zero-dependency, mobile-friendly first-resume builder.

## Run locally
1. Open `index.html` in a modern browser.
2. Fill in the form and choose **Update my resume**.
3. Choose **Print / Save PDF** and select “Save as PDF” in the print dialog.

No account, build step, external library, API, or database is required. The form runs entirely in the browser; it does not transmit or persist answers.

## Deploy free with GitHub Pages
1. Create a GitHub account if needed.
2. Create a **public** repository named `firststep-mvp`.
3. Upload `index.html` (and optionally this README) to the repository's root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/(root)`, then click **Save**.
7. Wait for deployment. Your URL will look like `https://YOUR-USERNAME.github.io/firststep-mvp/`.

If GitHub Pages offers only GitHub Actions or the deployment fails, use the official Vite/GitHub Pages docs only if you later upgrade to a build-tool project. This current single-file app does not require Vite.

## Before sharing publicly
- Test on phone and desktop.
- Review every generated resume for accuracy.
- Avoid collecting sensitive personal data or promising jobs.
- Check GitHub's current Pages terms and limits.
