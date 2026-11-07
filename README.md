# patriotcrypto.us

Static site for Patriot Crypto. No build step: `public/index.html` is the whole site.

- `public/index.html` - the whole page: styles, script and the animated inline-SVG logo, all in one file
- `public/logo.svg` - standalone (static) copy of the Patriot Crypto logo
- `public/og.png` - 1200x630 preview image used when the site is shared
- `public/favicon.svg` - site icon
- `public/_headers` - security headers
- `wrangler.jsonc` - tells Cloudflare to publish the `public/` folder

Deploy: Cloudflare connects to this repo, leaves the build command blank, and runs `npx wrangler deploy`.
