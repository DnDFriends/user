# D&D Friends Character Creator — GitHub Pages Front Door

This repository gives your Google Apps Script character creator a cleaner public-facing GitHub Pages URL.

## 1. Add your Apps Script URL

Open `index.html`.

Find:

    PASTE_YOUR_GOOGLE_APPS_SCRIPT_WEB_APP_URL_HERE

Replace it with the deployed Google Apps Script **Web app URL** ending in `/exec`.

Save the file.

## 2. Upload to GitHub

Create a new public GitHub repository (for example `dnd-character-creator`) and upload:

- `index.html`
- `README.md`
- `.nojekyll`

Commit the files to the `main` branch.

## 3. Enable GitHub Pages

In the repository:

1. Open **Settings**
2. Open **Pages**
3. Under **Build and deployment**, choose **Deploy from a branch**
4. Branch: **main**
5. Folder: **/(root)**
6. Click **Save**

GitHub will publish the site. Its address will normally look like:

    https://YOUR-USERNAME.github.io/dnd-character-creator/

Your Google Sheet can remain private. The GitHub page is only the public front door; the actual character creator continues running through your Apps Script deployment.

## Optional: custom domain

If you later own a domain, GitHub Pages also supports a custom domain such as `creator.example.com`.
