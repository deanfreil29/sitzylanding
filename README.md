# sitzy.co

Static landing site for Sitzy. No build step: plain HTML, CSS, and JS.

## Files
- `index.html` — landing page
- `privacy.html`, `terms.html` — legal pages (served at `/privacy` and `/terms`)
- `404.html` — not-found page
- `styles.css`, `main.js` — styles and small scripts (mobile menu, scroll reveal)
- `assets/` — logo, social share image, self-hosted fonts
- `email/sitzy-email-logo.png` — logo used by the Zoho email signature

## Deploy on Cloudflare Pages
1. Push this folder to a GitHub repo (files at the repo root).
2. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git → pick the repo.
3. Build settings: Framework preset **None**, build command **empty**, build output directory **/**.
4. Deploy, then add `sitzy.co` under the project's Custom domains.

Every push to `main` redeploys automatically.
