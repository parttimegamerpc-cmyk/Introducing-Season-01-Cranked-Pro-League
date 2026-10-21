CRANKED PRO LEAGUE — GITHUB PAGES IMAGE FIX

Why the poster was missing
The HTML refers to ./assets/cpl-promo.webp, but the previous website package did not include that asset. GitHub Pages cannot display a local image if its file is missing from the published repository.

Files in this package
- index.html
- assets/cpl-promo.webp

How to publish the fix
1. Open the GitHub repository for your site.
2. Upload/replace index.html at the repository root.
3. Upload the assets folder and make sure cpl-promo.webp is inside it.
4. Commit the changes to the branch/folder configured for GitHub Pages.
5. Refresh the published site. If needed, hard-refresh with Ctrl+Shift+R.

Important
Keep the filename exactly cpl-promo.webp (all lowercase) and preserve the assets folder. GitHub Pages paths and filenames are case-sensitive. Do not upload the entire CPL_GitHubPages_Fix folder as a nested folder unless your Pages source is configured to publish from that folder.
