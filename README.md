# Ronny Donkor — Still Becoming

Public website: https://still-becoming.ronnydonkor7.workers.dev/

The complete project is preserved. This repository remains private; Cloudflare Workers serves the public static website independently of GitHub Pages.

## Deployment

`worker.js` serves `index.html` as a text module. Deploy from this repository using `npx wrangler deploy` with an authorized Cloudflare account. Configuration is in `wrangler.jsonc`; no credentials belong in this repository.

HTML, CSS, images and browser JavaScript are necessarily visible to visitors. Server implementation and repository history remain private. This static portfolio has no database or secret bindings.

RAREST storefront: https://rarestfashionofficial.com/

[Hosting troubleshooting](TROUBLESHOOTING.md)
