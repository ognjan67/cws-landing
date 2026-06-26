# cws-landing

Statična landing stranica za **cws-ng.org** (BS na `/`, EN na `/en/`).
Deploy: automatski na Cloudflare na svaki `git push` (Workers static assets).

- `index.html` — BS
- `en/index.html` — EN
- `elektronika-logo.png` — logo
- `wrangler.toml` — Cloudflare config (Worker `cws-landing`, assets = root)

Uredi HTML → `git commit` → `git push` → Cloudflare deploya cijelo stablo.
