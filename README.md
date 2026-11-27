# Project Program Professionals

A website built with WalkThru Builds.

## Files

- `index.html` — Home
- `about.html` — About
- `videos.html` — Videos
- `store.html` — Store
- `contact.html` — Contact
- `.nojekyll` — tells GitHub Pages to serve these files as-is

## Publish with GitHub Pages

1. Create a new repository on GitHub (public, and do not add a README or .gitignore).
2. Upload the contents of this folder to the repository root and commit.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. Wait a minute: your site is live at `https://<your-username>.github.io/<repository-name>/`.

Every page links to the others by file name, so navigation works on GitHub Pages
without any extra setup. To use a custom domain, add a `CNAME` file with your
domain and point its DNS at GitHub Pages.

## Notes

- Each page carries its own CSS and JavaScript, so page styles never conflict.
- Images are embedded in the pages themselves, so the site works with no external hosting.
