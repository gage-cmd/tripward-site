# tripward.dev soft lander (APPROVED)

GitHub Pages · custom domain `tripward.dev` · CNAME file committed.

## Status

- [x] Repo + Pages site built
- [x] `CNAME` → `tripward.dev`
- [x] Approved Days 8–14 copy live in `index.html`
- [x] Waitlist → mailto `waitlist@tripward.dev` (Beehiiv later)
- [ ] Namecheap DNS (Gage)
- [ ] Pages → Enforce HTTPS (after DNS verifies)
- [ ] Stripe Payment Link for Founding Pro

## Namecheap — what Gage clicks

Domain List → **tripward.dev** → **Advanced DNS**

1. **Delete** any **URL Redirect Record** / parking / old A for `@` and `www`
2. **Add** these records:

| Type | Host | Value | TTL |
|------|------|-------|-----|
| A Record | `@` | `185.199.108.153` | Automatic |
| A Record | `@` | `185.199.109.153` | Automatic |
| A Record | `@` | `185.199.110.153` | Automatic |
| A Record | `@` | `185.199.111.153` | Automatic |
| AAAA Record | `@` | `2606:50c0:8000::153` | Automatic |
| AAAA Record | `@` | `2606:50c0:8001::153` | Automatic |
| AAAA Record | `@` | `2606:50c0:8002::153` | Automatic |
| AAAA Record | `@` | `2606:50c0:8003::153` | Automatic |
| CNAME Record | `www` | `gage-cmd.github.io` | Automatic |

3. Save → wait for propagation (often minutes, up to 48h)

## GitHub Pages checklist (after DNS)

1. Open https://github.com/gage-cmd/tripward-site/settings/pages
2. Custom domain = `tripward.dev` (already set via CNAME)
3. Check DNS check passes
4. Enable **Enforce HTTPS**

## OUT (do not add)

Fake install counts · Cursor-as-supported · Billscroll / Paywire / FuseCap user copy
