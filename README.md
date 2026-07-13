# Updating the resume

1. Edit `index.md`.
2. Commit and push the change to `main`.
3. The **Generate resume PDF** GitHub Actions workflow waits for the updated GitHub Pages site, prints it to `Andrew-Wilkes-Resume.pdf`, and commits the refreshed PDF automatically.

The workflow can also be started manually from the repository's **Actions** tab. The print-only CSS in `index.md` hides the site title, download button, and footer, uses compact font sizing, and keeps each work-experience entry together across page breaks.

## Manual fallback

Open <https://wilkesybear.github.io/>, print the page, and choose **Save as PDF**. Use Letter paper at 100% scale, turn headers and footers off, and turn background graphics on. Save the file as `Andrew-Wilkes-Resume.pdf` in the repository root, then commit and push it.
