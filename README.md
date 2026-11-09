# CloudSaver AI

> Free, browser-only AWS cost waste scanner. With the free scanner, your bill CSV never leaves your machine. (The paid $19 Pro Audit receives your CSV by email — see the privacy policy.)

The free scanner reads one monthly billing .csv from a single account and a single billing period **entirely in your browser** and outputs a **list of cost signals worth reviewing** — what looks like waste and what to check before you touch anything. No upload, no account, no auto-delete.

## Why it's open source
- Pure front-end (HTML + client-side JS). The scanner logic runs in your browser, so you can read every line and confirm **the free scanner never sends your CSV off the page**.
- Open source is the strongest proof of that claim.
- The scanner is free. Real revenue is the **$19 Pro Audit** (a founder reviews the billing CSV you send by email and writes up what to check first) — not the code.

## Core features
- **Free scanner: 100% client-side**: its CSV is parsed in your browser only. Nothing is uploaded to any server. The paid Pro Audit is a separate email-based service.
- **Cost signals to review**: what looks like waste and what to verify before making any change.
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
The scanner is free. If you want a founder-reviewed write-up of the cost signals in your billing CSV and what to check first, buy the **$19 Pro Audit** and we deliver it by email.

## Disclaimer
- The tool gives suggestions, it does not delete anything for you. Verify before deleting.
- Not an AWS product; not affiliated with Amazon.
- With the free scanner, your bill CSV stays in your browser. The $19 Pro Audit receives that CSV by email; see the privacy policy.

## License
MIT — see [LICENSE](LICENSE).
