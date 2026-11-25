# Body & Science — Public Website

This repository contains the public-facing website and public institutional documents for **Body & Science**.

- Repository: `body-and-science.github.io`
- Intended publishing platform: GitHub Pages
- Technology: static HTML, CSS and JavaScript
- Backend: none
- External frameworks/CDNs: none

## 1. Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository named exactly `body-and-science.github.io`.
2. On the repository page, choose **Add file → Upload files**.
3. Upload the contents of this folder (not the ZIP file itself). Ensure `index.html` is at the repository root.
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/ (root)`, then save.
8. Wait for the Pages deployment to finish. Visit `https://body-and-science.github.io/`.

GitHub's interface may change slightly. If Pages asks you to confirm a source, choose the `main` branch and root folder.

## 2. Upload from an Android phone

1. Download and extract the ZIP on your phone.
2. Open the repository in Chrome and switch to Desktop site if the upload controls are difficult to find.
3. Use **Add file → Upload files** and select all extracted files and folders.
4. Check that `index.html`, `assets/`, `documents/` and the other `.html` files appear at the top level.
5. Commit changes.

If selecting a whole folder is not supported by the mobile file picker, use GitHub's web upload in desktop mode or the GitHub mobile app/browser file picker to upload the extracted folder contents while preserving folder paths.

## 3. Update the site

Edit a page directly in GitHub using the pencil icon, or replace the file with an updated version. Every commit becomes part of the repository's history. Keep `index.html` at the root.

## 4. Important publication safeguards

- This is a static public website. Anything committed here can be read, copied and downloaded by anyone.
- Never commit passwords, API keys, access tokens, private personal information, private research data or confidential documents.
- No Supabase or backend credentials are required for this website.
- Do not publish identifiable participant data, medical records or unpublished research material.
- The constitutional charter is a founding draft, not a legally operative registration document.
- The site does not claim that Body & Science has been registered, received tax exemption, or obtained statutory recognition.
- Replace draft wording only after the relevant decisions have been formally approved.

## 5. Suggested next additions

1. Finalise and legally review the institutional objects and governing documents.
2. Publish approved scientific integrity, research ethics, quality and financial policies.
3. Add verified contact information and leadership details only after confirmation.
4. Add annual reports and financial statements only after they exist and are approved for publication.

## 6. Local preview

Open `index.html` in a browser. For a more reliable local preview, run a simple static server from this directory, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/`.
