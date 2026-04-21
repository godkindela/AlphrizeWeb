# Alphrize Website

Static marketing site for deployment on Cloudflare Pages.

## Local preview

Open [index.html](./index.html) directly in a browser for a quick preview.

For a Pages-like local server:

```bash
npx wrangler pages dev .
```

## Deploy

Authenticate first:

```bash
npx wrangler whoami
```

Then deploy:

```bash
npx wrangler pages deploy . --project-name=alphrize
```

## Domain

After deployment, attach the custom domain in Cloudflare Pages or with Wrangler-compatible account access:

- `alphrize.com`
- optionally `www.alphrize.com`
