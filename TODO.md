# TODO
- [ ] Inspect index.html for existing screenshot viewer logic and project screenshot/doc data.
- [ ] Rename on-disk folder `assets/screenshots/EA:CPP/` → `assets/screenshots/EA-CPP/` (colon fix) and update all asset paths in `cpp-oop` arrays.
- [ ] Split `cpp-oop` assets: keep only image files in `projectScreenshots['cpp-oop']`; move `.doc` files to new `projectDocuments['cpp-oop']`.
- [ ] Implement new full-size overlay `#photo-viewer-overlay` with Picture and Fax Viewer UI (titlebar, dominant image, prev/next, counter, close behaviors).
- [ ] Update “View Screenshots” handler to open new overlay; remove/disable old small viewer code path so no dead code remains.
- [ ] Render doc download links under the screenshot button on the cpp-oop project card.
- [ ] Verify: open site, test viewer navigation, doc downloads, overlay close (X, backdrop click, Escape).

