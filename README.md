# WENSLink Open Source

Static project hub, published at https://wenslink-os.github.io/.

## Deployment status

Verified on 2026-09-30: the public repository `wenslink-os/wenslink-os.github.io` serves GitHub Pages from `main` at `/(root)` on GitHub's default domain, and the hub is live at https://wenslink-os.github.io/. No custom domain is configured. The site is deployed through GitHub Pages. Check the repository's Actions tab for the status of later updates.

## Publish

1. Sign in as `wenslink-os`.
2. Create the public repository **`wenslink-os.github.io`**. If it already exists, inspect it and preserve existing work.
3. Upload `index.html`, `README.md`, `LICENSE`, `.nojekyll`, and the `assets/` directory at the repository root, on `main`.
4. In Settings → Pages, select Deploy from a branch → main → /(root).
5. Wait for the deployment to succeed and check https://wenslink-os.github.io/.

No custom-domain setting, purchased domain, DNS record, API key, or build step is needed.
Keep the existing `break-your-assumptions` repository and Pages deployment intact.

## Local preview

Open `index.html` in a browser, keeping the `assets/` directory beside it. Styles and the small Star button script are included in the HTML. Logo images and the favicon are in `assets/`; no install is needed.
The linked projects and GitHub pages require internet access.

## Add a project

Copy the existing `<article class="project">` block within the projects section.
Replace its title, description, topics, demo, source, and release URLs with verified details.
Use a unique title ID and matching `aria-labelledby`. Update the collection label to match.
Only list real published projects; no automatic discovery or background updates are configured.

## Writing and layout

Use simple, conversational language. Avoid long dashes in all new or edited copy. Keep prose paragraphs justified, with the final line aligned to the start. Keep headings, navigation, and buttons easy to scan.

## Checks

### Reported checks

These checks were run at publication on 2026-09-30 and reported to the maintainer. They are recorded here as reported.

- The repository was created public and the four files (`index.html`, `README.md`, `LICENSE`, `.nojekyll`) were committed to the root of `main` with the account's no-reply identity.
- The `index.html` in the repository matched the prepared file byte for byte (SHA-256).
- The Pages deployment completed successfully.
- The live page loaded, styles rendered, and the Projects navigation link worked.
- No horizontal overflow was found at simulated widths of 320, 375, 390, 768, and 1280 px.
- The hub's project links (demo, source, releases, contribution guide) opened without errors.

### Earlier checks on 2026-09-30

These checks were recorded during an earlier README update, before the About section, logo, and Star button were added. They describe that version.

- https://wenslink-os.github.io/ loads with the title "WENSLink Open Source" and the heading "Explore the idea. Open the source.". The served `index.html` is byte-identical (SHA-256) to the prepared file, and `/.nojekyll` returns 200.
- Pages workflow runs 2 to 4 completed successfully; run 1 was cancelled.
- Styles apply (the project card renders as a grid) and the Projects link scrolls to `#projects`.
- No horizontal overflow at 320, 375, 390, 768, and 1280 px, measured in iframes of those widths.
- The demo https://wenslink-os.github.io/break-your-assumptions/ returns 200 with its expected title. The source repository page and `CONTRIBUTING.md` return 200 in an unauthenticated fetch.

### Latest browser checks on 2026-09-30

- The live hub contains the revised, plain-language copy and no long dashes in its HTML. All seven prose paragraphs use justified alignment.
- The About link opens `#about`. The three logo images load, all heading labels resolve, and there are no duplicate IDs. No horizontal overflow was found at the 1363 px desktop viewport.
- The Star button glow was observed before dismissal. Stop animation moved focus to the Star link, and dismissal persisted after reload. The Star link opened the hub repository in a new tab without changing its label. A click does not confirm that a GitHub star was given.
- Pages workflow run 12 for site commit `5a7265a` completed successfully.

### Limitations

- Mobile layouts were checked at simulated widths, not on a physical phone.
- Full keyboard-only navigation, screen readers, and browsers other than Chrome have not been tested. The latest copy change was checked at a desktop viewport; the earlier simulated mobile checks apply to the earlier version.

## License

MIT. Project links retain each project's own license.
