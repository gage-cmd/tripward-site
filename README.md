# tripward.dev soft lander

Static Days 8–14 lander (GitHub Pages).

## DNS (Namecheap → Advanced DNS)

Point apex `tripward.dev` at GitHub Pages:

| Type | Host | Value | TTL |
|------|------|-------|-----|
| A | @ | 185.199.108.153 | Automatic |
| A | @ | 185.199.109.153 | Automatic |
| A | @ | 185.199.110.153 | Automatic |
| A | @ | 185.199.111.153 | Automatic |
| AAAA | @ | 2606:50c0:8000::153 | Automatic |
| AAAA | @ | 2606:50c0:8001::153 | Automatic |
| AAAA | @ | 2606:50c0:8002::153 | Automatic |
| AAAA | @ | 2606:50c0:8003::153 | Automatic |

Optional www:

| Type | Host | Value |
|------|------|-------|
| CNAME | www | gage-cmd.github.io |

Remove Namecheap parking / URL redirect for `@` if present.

## After DNS

In repo Settings → Pages → Custom domain: `tripward.dev` → Enable HTTPS.

## Todo

- Wire waitlist to Beehiiv (or Formspree) — currently localStorage only soft capture
- Set Founding Pro Stripe link on `#founding` button
