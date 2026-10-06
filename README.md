# Poojitha Sonam — Résumé Portfolio

A clean résumé-style portfolio in a single HTML file, with responsive layout, work history, education, skills, a previous research project, and a print / save-as-PDF button.

## Upload to GitHub Pages

1. Extract the ZIP.
2. Create or open your GitHub repository.
3. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root. If replacing the previous version, overwrite `index.html` and remove the old `assets/southwest-fuel-attendee-list.xlsx` file and empty assets folder from the current repository.
4. In Settings → Pages, select Deploy from a branch, `main`, and `/ (root)`.
5. Open the URL shown by GitHub after deployment finishes.

No build, dependencies, external fonts, or installation are required. Open `index.html` locally to preview.

## Online project viewing

The Previous Project section links to this Google Drive folder:
https://drive.google.com/drive/folders/10ManGoFRn3XCSaODkKh-dK8quJqdZZX_

Visitors click View project in Google Drive, then select the workbook to preview it in Drive. This is a folder link, not a direct workbook link or embedded spreadsheet. No spreadsheet download is required by the portfolio.

Drive access could not be verified during preparation. In Drive, set the folder and workbook to the intended viewer permissions. If you want any recruiter with the link to view it, use General access → Anyone with the link → Viewer, if available for your account. Test in a signed-out/incognito window before sharing the portfolio.

To open the exact workbook instead of the folder, copy the workbook's own Share link and replace the URL in the project-link anchor in `index.html`.

## Editing

All content and CSS are in `index.html`. Update the résumé, availability, or dates directly. Colors are defined in the CSS `:root` block. The project section identifies the Excel workbook as a previous project. Counts were checked against the supplied updated attachment: 267 populated contact rows across four business verticals. These are record counts, not deduplicated people.

The Excel file is not bundled in this revised project. Keep any publicly shared contact data subject to your sharing permissions; use an anonymized work sample if needed. Removing an old file from a public Git repository does not erase its commit history.
