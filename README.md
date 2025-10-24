# AFUGR Landing Page

A simple landing page for AFUGR, deployed on Cloudflare Pages at [afugr.com](https://afugr.com).

## Deployment

This site is automatically deployed to Cloudflare Pages when changes are pushed to the main branch.

### Cloudflare Pages Setup

1. Connect this repository to Cloudflare Pages
2. Set build settings:
   - Build command: (none needed for static HTML)
   - Build output directory: `/`
3. Configure custom domain: `afugr.com`

## Local Development

Simply open `index.html` in your browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`

## License

All rights reserved.
