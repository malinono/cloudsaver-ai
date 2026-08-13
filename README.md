# CloudSaver AI

> Free, browser-only AWS cost waste scanner. Your bill CSV never leaves your machine.

CloudSaver reads your AWS Cost & Usage Report (CUR) CSV **entirely in your browser** and outputs a **safe-delete checklist** — what's likely waste, what order to remove it in, and what to check before you touch anything. No upload, no account, no auto-delete.

## Why it's open source
- Pure front-end (HTML + client-side JS). The scanner logic runs in your browser, so you can read every line and confirm **your data never leaves the page**.
- Open source is the strongest proof of that claim.
- The scanner is free. Real revenue is the **$19 Pro Audit** (a human double-checks your plan before you run it) — not the code.

## Core features
- **100% client-side**: the CSV is parsed in your browser only. Nothing is uploaded to any server.
- **Safe-delete checklist**: what to delete / in what order / what to verify first.
- **No auto-delete**: you keep the final say.
- **Free + open source**.

## Run it
- Simplest: open `index.html` in any browser.
- Or host the static files anywhere (GitHub Pages / Cloudflare Pages).
- No backend, no API key, no account required.

## Repo layout
- `index.html` — landing page + the scanner (scanner logic is inline client-side JS)
- `pro-audit.html` — $19 Pro Audit intake page
- `blog-aws-billing-csv.html` / `blog-aws-waste.html` / `blog-aws-cost-optimization.html` — blog posts
- `report-template.html` — sample report template
- `terms.html` / `privacy.html` — legal pages

## Pro Audit ($19 one-time)
The scanner is free. If you want a human review plus a prioritized, executable delete plan, buy the **$19 Pro Audit** and we deliver a safe-delete report.

## Disclaimer
- The tool gives suggestions, it does not delete anything for you. Verify before deleting.
- Not an AWS product; not affiliated with Amazon.
- Your data stays in your browser; we do not store your bill.

## License
MIT — see [LICENSE](LICENSE).
