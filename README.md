# WENSLink Open Source

Static project hub, published at https://wenslink-os.github.io/.

## Deployment status

Verified on 2026-09-30: the public repository `wenslink-os/wenslink-os.github.io` serves GitHub Pages from `main` at `/(root)` on GitHub's default domain, and the hub is live at https://wenslink-os.github.io/. No custom domain is configured. The `pages build and deployment` run for the last site commit (run 4) completed successfully.

## Publish

1. Sign in as `wenslink-os`.
2. Create the public repository **`wenslink-os.github.io`**. If it already exists, inspect it and preserve existing work.
3. Upload `index.html`, `README.md`, `LICENSE`, and `.nojekyll` at the repository root, on `main`.
4. In Settings → Pages, select Deploy from a branch → main → /(root).
5. Wait for the deployment to succeed and check https://wenslink-os.github.io/.

No custom-domain setting, purchased domain, DNS record, API key, or build step is needed.
Keep the existing `break-your-assumptions` repository and Pages deployment intact.

## Local preview

Open `index.html` in a browser. It contains all styles and a favicon; no install is needed.
The linked projects and GitHub pages require internet access.

## Add a project

Copy the existing `<article class="project">` block within the projects section.
Replace its title, description, topics, demo, source, and release URLs with verified details.
Use a unique title ID and matching `aria-labelledby`. Update the collection label to match.
Only list real published projects; no automatic discovery or background updates are configured.

## Checks

### Reported checks

These checks were run at publication on 2026-09-30 and reported to the maintainer. They are recorded here as reported.

- The repository was created public and the four files (`index.html`, `README.md`, `LICENSE`, `.nojekyll`) were committed to the root of `main` with the account's no-reply identity.
- The `index.html` in the repository matched the prepared file byte for byte (SHA-256).
- The Pages deployment completed successfully.
- The live page loaded, styles rendered, and the Projects navigation link worked.
- No horizontal overflow was found at simulated widths of 320, 375, 390, 768, and 1280 px.
- The hub's project links (demo, source, releases, contribution guide) opened without errors.

### Rechecked on 2026-09-30

These checks were rerun while updating this README.

- https://wenslink-os.github.io/ loads with the title "WENSLink Open Source" and the heading "Explore the idea. Open the source.". The served `index.html` is byte-identical (SHA-256) to the prepared file, and `/.nojekyll` returns 200.
- Pages workflow runs 2 to 4 completed successfully; run 1 was cancelled.
- Styles apply (the project card renders as a grid) and the Projects link scrolls to `#projects`.
- No horizontal overflow at 320, 375, 390, 768, and 1280 px, measured in iframes of those widths.
- The demo https://wenslink-os.github.io/break-your-assumptions/ returns 200 with its expected title. The source repository page and `CONTRIBUTING.md` return 200 in an unauthenticated fetch.

### Limitations

- Mobile layouts were checked at simulated widths, not on a physical phone.
- Keyboard-only navigation, screen readers, and browsers other than Chrome were not tested.

## License

MIT. Project links retain each project's own license.
