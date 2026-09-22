# AIcademy Site

Static marketing and support pages for AIcademy, published with GitHub Pages from `main` at https://awfasano.github.io/aicademy-pages/.

## Pages

- `/` marketing homepage
- `/aicademy-3.html` version 3 launch article and first-session guide
- `/study-notes-to-practice.html` five-step study guide
- `/help.html` support
- `/privacy.html` privacy

## September 21, 2026 launch update

Version 3.0 is publicly available on the App Store, verified September 21. The homepage and study guide now describe available features. The launch article provides a practical starting point, and every marketing page links directly to the App Store. Original AP starter resources cover Biology, Calculus AB, and U.S. History; the copy states the relevant product limits.

Search metadata includes canonical URLs, social cards, descriptive titles, and factual SoftwareApplication structured data. `sitemap.xml` includes all five public pages. The crawler discovery file must also be published at the origin root, `https://awfasano.github.io/robots.txt`, which is maintained in `awfasano/awfasano.github.io`. The copy here only becomes authoritative if this project is later served at a custom-domain root.

The Google site-verification meta tag identifies the owner's Search Console property; retain it after verification. Search Console acceptance is distinct from Google indexing or ranking a page.

No tracking, external fonts, or mailing-list signup is installed. Support and privacy content is preserved.

For local preview, run `python3 -m http.server 8126 --bind 127.0.0.1` in this directory.

## Custom domain status

GitHub Pages currently has no custom domain configured. `theaistudytool.com` uses Cloudflare DNS and serves a separate placeholder. Do not switch canonical URLs or sitemap addresses until the domain is actually connected and HTTPS is working. A custom-domain migration requires updating the canonical, Open Graph, structured-data, robots and sitemap URLs together, then verifying the new Search Console property.
