# Mercury — A Tale of Two Coins

A complete static website, including the final reciprocity illustration.

## Files

- `index.html` — the complete page and its editable text.
- `styles.css` — layout, colours, typography and responsive styling.
- `images/` — all ten illustrations, including `reciprocity.png`.
- `.nojekyll` — tells GitHub Pages to serve the static files without Jekyll processing.

There are no package installations, build commands, API keys, databases or paid services required by these files. Images and styling use relative paths, so the site works at a repository URL such as `/mercury/`.

## Preview on your computer

Extract the entire ZIP, then open `index.html` in your browser. Keep the stylesheet and images folder alongside it.

## Publish on GitHub Pages

1. Use your existing `becseth88/mercury` repository, or create a new public repository for free GitHub Pages hosting.
2. Upload or commit the extracted files and the `images` folder to the repository root. `index.html` must be directly in the root, not inside another enclosing folder. Upload the extracted contents, not the ZIP itself.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the branch containing these files (usually `main`), choose **/(root)**, and save.
5. After publication completes, use the website link shown in Pages settings.

If you use your existing `mercury` repository, the page will be at:
https://becseth88.github.io/mercury/

Uploading this `index.html` to the existing publishing location replaces the old page. Git history retains committed earlier versions. If the original page should remain live separately, use a different repository for this edition.

## Editing

Edit text in `index.html` and styling in `styles.css`, then commit the updated files. Keep image names and their paths in the HTML in agreement.

This export retains all ten illustrations and the revised story. The footer link labelled “The original story” was removed from the export because it would point back to itself when this version is hosted at your original `/mercury/` address.

GitHub's official publishing instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Packaged 30 September 2026.
