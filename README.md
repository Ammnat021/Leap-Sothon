# Leap Sothon – CV website

A static site (no build step). Files:

- `index.html` – the whole site (HTML, CSS, JS)
- `assets/photo.jpg` – your portrait
- `assets/Leap_Sothon_CV.pdf` – the download button points here
- `.nojekyll` – tells GitHub Pages to serve files as they are

## Publish with GitHub Pages

1. On github.com click **New repository**. Name it `leapsothon.github.io` (replace with your GitHub username: `<username>.github.io`) for a clean address, or any name such as `cv`. Keep it **Public**.
2. Upload these files (**Add file > Upload files**), or from this folder run:
   ```
   git init
   git add .
   git commit -m "CV website"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. In the repository open **Settings > Pages**. Under **Build and deployment** choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<username>.github.io/` (or `https://<username>.github.io/<repo>/` for other repo names).

## Editing
Change text directly in `index.html`. Replace the CV by overwriting `assets/Leap_Sothon_CV.pdf`. Commit and push; the site updates in about a minute.
