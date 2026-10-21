# Wheel Strategy Tracker — Public landing page

Static GitHub Pages website for **wheelstrategytracker.com**.

## Deploy
1. Create a public GitHub repository named `WheelStrategyTracker`.
2. Upload the **contents** of this folder to the repository root.
3. In Settings → Pages, publish from `main` / root.
4. In Settings → Pages, set custom domain to `wheelstrategytracker.com`.
5. Configure DNS for GitHub Pages and wait for HTTPS certificate provisioning.

## Checkout
Edit `config.json` to set `checkout_url` to the **existing verified Trader Repository checkout URL for this specific product**. Currently Buy Now goes to the Trader Repository homepage, **not a functioning product checkout**. Do not deploy a fake or guessed checkout URL.

## Visual assets
- `assets/logo.svg`: editable vector logo
- `assets/favicon.svg`: browser icon
- The chart graphic is an illustrative SVG, not an actual product screenshot. Replace with real screenshots/videos when available.

No license recovery, account system, or subscription features are included. BTC confirmation and protected download handling remain in the existing centralized Cloudflare system.
