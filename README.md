# Nordform Living — Interactive 3D Furniture Store (Demo)

A premium furniture e-commerce concept built around a **real-time 3D product showroom**: customers rotate furniture 360°, swap fabrics and wood finishes on the live model, configure their exact piece, and check out — all in one page.

**Live demo:** _deployed on Vercel (link in repo About)_

## Highlights

- **Interactive 3D viewer** (Three.js / WebGL) — drag to rotate, scroll/pinch to zoom, auto-spin toggle, reset view
- **3 configurable products** — armchair, sofa, floor lamp, each with 6 fabric options and 3 wood finishes that restyle the actual 3D materials
- **Live price math** — premium fabrics/finishes adjust the price in the panel, the viewer badge, and the cart
- **Room-mood previews** — Bright Studio / Warm Lounge / Evening lighting themes
- **Working cart** — quantity controls, slide-out drawer, subtotals, persisted in `localStorage`
- **Demo checkout** — full checkout flow with order confirmation (clearly labeled demo; no real payment)
- **Wishlist**, product dimensions with fit guide, materials & care info, stock and delivery-date estimates
- **Showroom booking form** with confirmation, plus full warranty / delivery / 100-night-trial terms
- **Graceful fallback** — if WebGL can't load, a product photo replaces the viewer and shopping keeps working
- Responsive and touch-friendly; keyboard-focus states and ARIA labels included

## Tech

- Three.js (r160) with procedurally built furniture models, ACES tone mapping, soft shadows, room-environment lighting
- Tailwind CSS via CDN, Fraunces + Manrope typography
- Vanilla JavaScript storefront logic (cart, wishlist, booking) with `localStorage` persistence — no build step

## Run it

Open `index.html` in any modern browser (internet needed for the CDN libraries), or deploy the repo to any static host — Vercel, Netlify, GitHub Pages.

## Note

Fictional demo storefront built as a portfolio piece: business details, prices, and testimonials are sample content.
