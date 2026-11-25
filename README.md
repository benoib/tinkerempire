# TinkerEmpire

We create cool stuff. Live at [tinkerempire.com](https://tinkerempire.com).

```
website/   static site, deployed on Cloudflare Workers (static assets)
  public/  the site itself (one page, no build step)
brand/     logo and icon, SVG + PNG, black and white
```

## Deploy

```bash
cd website && npx wrangler deploy
```

`wrangler.jsonc` binds the custom domains `tinkerempire.com` and `www.tinkerempire.com`.
