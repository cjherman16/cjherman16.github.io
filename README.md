# Charlie Herman — portfolio

A plain HTML/CSS site with no build step, ready to host for free on GitHub Pages.

## Put it online

1. Sign in to github.com and create a new **public** repository named `YOUR-USERNAME.github.io` (use your real GitHub username). Leave "Add a README" unchecked.
2. On the new repo's page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `style.css`, `README.md` and the `images` and `files` folders. Then click **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then click **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

To change something later, open the file on GitHub, click the pencil icon, edit and commit. The site updates in about a minute.

## Things to finish

- **Photo for the Hot Wheels car:** save images (a CAD render, Moldflow result or FEA plot) in `images/`, then uncomment the `<figure>` block under each project and set the file name.

## Files

- `index.html` — all the text on the page
- `style.css` — colors, fonts and layout. The colors are at the top under `:root`.
- `images/` — project photos
- `files/` — résumé and project reports (PDF)
