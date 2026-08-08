# 404 Workshop placeholder site

A single-file static placeholder for 404workshop.com.

## Cloudflare Pages

The easiest deploy path is to create a Pages project and upload this folder, or connect a GitHub repo containing `index.html`.

No framework, build command, package manager, or dependencies are required.

The included `_redirects` file permanently redirects every
`www.404workshop.com` path to the same path on `https://404workshop.com`.
Add both hostnames as Cloudflare Pages custom domains so the redirect can run.

`sitemap.xml` lists the canonical homepage for search engines, and `robots.txt`
publishes the sitemap location. Add new public page URLs to the sitemap as the
site grows; in-page anchors such as `#about` are not separate pages.

## Before launch

Edit `index.html` and replace the placeholder MakerWorld link (`href="#"`) with the real URL.
