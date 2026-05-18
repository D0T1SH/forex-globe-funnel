# Forex Globe — 1on1 Mentorship Funnel

Modernized 3-step funnel for Abdul Light / Forex Globe.

## Pages

| Step | File | URL on Vercel |
|------|------|---------------|
| 1. Landing + VSL | `index.html` | `/` |
| 2. Application | `apply.html` | `/apply` |
| 3. Thank You / Book Call | `thank-you.html` | `/thank-you` |

## Deploy

Static site. No build step. `vercel.json` handles clean URLs.

Just push to GitHub and connect on [vercel.com/new](https://vercel.com/new) — Vercel auto-detects it.

## Editing copy / swapping assets

- **VSL embeds**: search for `wistia.net/embed/iframe` in `index.html` and `thank-you.html`
- **Testimonial videos**: search for `youtube.com/embed` and `player.vimeo.com` in `index.html`
- **Payout screenshots**: the `payouts` array near the bottom of `index.html`
- **Calendly link**: search for `calendly.com/abdullight` in `thank-you.html`
