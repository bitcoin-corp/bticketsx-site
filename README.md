# bTicketsX.com

**Licence: [Open BSV License version 4](LICENSE)**, © The Bitcoin Corporation Ltd. (GitHub labels it "Other" because it is not on GitHub's standard licence list.)

Marketing site for **bTicketsX**, tickets you actually own. By The Bitcoin Corporation Ltd. Static HTML in the b*X house shell (shell.css, same as bphotosx.com / bdrivex.com / bgitx.com; only `--xs-acc` differs: lime `#C8F03C`).

Status: **coming**. Nothing on the page may be stated as live until it is. Copy: say "ticket", never token/NFT/value; no "first"/"pioneers".

## Develop

```
pnpm install
pnpm build   # html-validate + local asset check
```

OG image source: `media-src/og-bticketsx-v2.html` (render 1200x630 with headless Chrome). Deploys from GitHub via Vercel (`vercel.json`: static, output `.`, main only).

## Licence

Open BSV License version 4. See `LICENSE`.
