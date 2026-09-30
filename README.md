# WENSLink Open Source

Static project hub prepared for https://wenslink-os.github.io/.

## Publish

1. Sign in as `wenslink-os`.
2. Create the public repository **`wenslink-os.github.io`**. If it already exists, inspect it and preserve existing work.
3. Upload `index.html`, `README.md`, `LICENSE`, and `.nojekyll` at the repository root, on `main`.
4. In Settings → Pages, select Deploy from a branch → main → /(root).
5. Wait for the deployment to succeed and check https://wenslink-os.github.io/.

No custom-domain setting, purchased domain, DNS record, API key, or build step is needed.
Keep the existing `break-your-assumptions` repository and Pages deployment intact.

This package is prepared source, not evidence that the repository or Pages site has been created.

## Local preview

Open `index.html` in a browser. It contains all styles and a favicon; no install is needed.
The linked projects and GitHub pages require internet access.

## Add a project

Copy the existing `<article class="project">` block within the projects section.
Replace its title, description, topics, demo, source, and release URLs with verified details.
Use a unique title ID and matching `aria-labelledby`. Update the collection label to match.
Only list real published projects; no automatic discovery or background updates are configured.

## Checks

The HTML structure and expected links were checked during preparation. Browser visual verification
and live deployment verification are pending. After publishing, check at mobile and desktop widths,
keyboard navigation, all outbound links, the existing project demo, and the Pages deployment result.

## License

MIT. Project links retain each project's own license.
