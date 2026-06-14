# Academic Website

A lightweight personal academic website designed for GitHub Pages. It is plain
HTML and CSS, so there is no build step, JavaScript, or dependency install.
The page content lives directly in `index.html`.

## Customize

1. Edit `index.html` for bio, links, papers, talks, teaching, and contact
   information. The main sections are marked with comments like `<!-- Papers -->`.
2. Replace `assets/picture.png` if you want a different profile photo.
3. Put your CV source in `cv/` and compile the public PDF as `cv/cv_CIALDEA.pdf`,
   or change the CV link in `index.html`.

## Preview Locally

Double-click `index.html`, or open it from your browser. Because the site is now
static HTML, local preview does not need a server.

## Publish On GitHub Pages

Option A, user site:

1. Create a GitHub repository named `YOUR-USERNAME.github.io`.
2. Push these files to the repository's `main` branch.
3. The site will be available at `https://YOUR-USERNAME.github.io/`.

Option B, project site:

1. Push these files to any GitHub repository.
2. In GitHub, open Settings -> Pages.
3. Set Source to "Deploy from a branch".
4. Choose branch `main` and folder `/ (root)`.
5. The site will be available at the Pages URL shown by GitHub.

The `.nojekyll` file is included so GitHub Pages serves the static files as-is.
