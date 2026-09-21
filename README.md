# AIcademy Site

Static marketing and support pages for AIcademy.

## Pages

- `/` marketing homepage
- `/help.html` support page
- `/privacy.html` privacy policy
- `/study-notes-to-practice.html` five-step study guide

## September 2026 marketing refresh

The homepage now links directly to the current App Store release, previews the upcoming version 3 AP features, and links to an original study article. Version 3 features are explicitly marked coming soon until the update is publicly available. The refresh includes responsive styling, keyboard focus states, native FAQ disclosures, canonical/share metadata, a social preview image, robots.txt, and a sitemap. No tracking, signup form, or external font dependency was added.

For a local preview, run `python3 -m http.server 8126` from this directory. The homepage and article were checked at desktop and phone widths, including download links, image loading, article navigation, FAQ toggles, and horizontal overflow. Support and privacy page content was preserved.

When version 3 is publicly downloadable, update the coming-soon announcement, preview labels, FAQ, and article sidebar together. A review approval by itself is not the public release.

## Custom domain

This repo is configured for:

- `theaistudytool.com`
