# patriotcrypto.us

Static site for Patriot Crypto. No build step: `index.html` is the whole site.

- `index.html` - the whole page: styles, script and the animated inline-SVG logo, all in one file
- `logo.svg` - standalone (static) copy of the Patriot Crypto logo
- `og.png` - 1200x630 preview image used when the site is shared
- `favicon.svg` - site icon
- `_headers` - security headers used by Cloudflare Pages

Deploy: connect this repo to a Cloudflare Pages project with no build command and `/` as the output directory.
