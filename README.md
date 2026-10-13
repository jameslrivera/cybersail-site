# Cyber Sail — club website

Static site, no build step. Edit `index.html` and `style.css` directly.

## Deploy on GitHub Pages (free)

1. Create a GitHub organization or account for the club (e.g. `cybersail-ccga`).
2. Create a repository named **`<org>.github.io`** (e.g. `cybersail-ccga.github.io`) — the site will be at `https://<org>.github.io`.
   Any other repo name works too; the site will then be at `https://<org>.github.io/<repo>`.
3. Upload these files to the repo root (`index.html`, `style.css`, `assets/`, `README.md`).
4. Repo **Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save**.
5. Wait ~1 minute. Done. Every push to `main` redeploys automatically.

## Custom domain (optional)

- Buy `cybersail.org` (or similar) from Cloudflare/Namecheap, ~$10–15/yr, **or** ask CCGA IT for a `ccga.edu` subdomain.
- Settings → Pages → Custom domain → enter it, then add the DNS records GitHub shows. Enable "Enforce HTTPS".

## Fill in the placeholders

Search `index.html` for these and replace:

- `DISCORD_INVITE_LINK`, `INSTAGRAM_LINK`, `ATTENDANCE_FORM_LINK`, `CLUB_EMAIL`
- `[ROOM]`, `[ROOM / BUILDING]`
- Officer `[Name]` / `[PHOTO]` (drop photos in `assets/` and swap the `.avatar` div for an `<img>`)
- Schedule rows marked `[Competition]`
- `assets/logo.svg` — replace with the final club logo
