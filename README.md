# Khayfer Giveaway × PoncakeA&A 🎉

Mobile-first giveaway landing page for the **Khayfer Liquidation × PoncakeA&A** Summer Giveaway.

## About the Giveaway
- **Dates:** May 19–23, 2025
- **Winner announced:** May 24, 2025
- **Prize:** Summer Gift Basket (~$50 ARV)
- **Hosted by:** Khayfer Liquidation, Russellville, AR
- **Pastry partner:** PoncakeA&A (available online & at Dreami Tea in Russellville, AR)

## Features
- 📱 Mobile-first design (max-width 480px), optimized for QR code scans
- 🌐 Full English/Spanish language toggle
- ✅ Entry form with client-side validation and thank-you confirmation
- 📌 Sticky "Enter Now" bottom bar that auto-hides when form is in view
- 📋 Legal disclaimer (No purchase necessary, Meta liability release) in both languages
- 🎨 Summer-themed design — Fredoka One + Nunito fonts, coral/orange/yellow palette

## How to Deploy
This is a single `index.html` file — just upload it to any static hosting (GitHub Pages, Netlify, etc.) or drop it on your server.

### GitHub Pages (quick option)
1. Go to **Settings → Pages** in this repo
2. Set source to `main` branch, `/ (root)`
3. Your page will be live at `https://hamandatorres.github.io/khayfer-giveaway/`

## Before Going Live — Replace Placeholder URLs
Search the `index.html` for the following comments and update the `href` values:

| Comment | What to replace |
|---|---|
| `REPLACE: PoncakeA&A Facebook URL` | PoncakeA&A's Facebook page URL |
| `REPLACE: Dreami Tea Facebook URL` | Dreami Tea's Facebook page URL |
| `REPLACE: Khayfer Liquidation Facebook URL` | Khayfer's Facebook page URL |
| `REPLACE: Khayfer Liquidation Instagram URL` | Khayfer's Instagram page URL |

All placeholder `href` values follow the pattern `https://www.facebook.com/REPLACE_...` — easy to find with Ctrl+F.

## Tech Stack
- Pure HTML, CSS, and vanilla JavaScript — no frameworks, no build tools
- Google Fonts CDN (Fredoka One + Nunito)
- Single file, zero dependencies
