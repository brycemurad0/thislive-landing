# this.live Landing Page

Static landing page for this.live LLC.

## Files

- `index.html` — page markup
- `style.css` — styles

## Deploy

No build step. Serve the directory as-is.

**Local preview:**

```bash
cd thislive-landing
python3 -m http.server 8000
# open http://localhost:8000
```

**Cloudflare Pages / Netlify / Vercel:**

Point the root directory to this folder and deploy. No configuration needed.

**Custom domain:**

Point your DNS A/CNAME record to your hosting provider and set the document root to this directory.
