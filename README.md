# Sweet Crumbs 🍰

A playful, mobile-first bakery storefront for Sweet Crumbs in Johar Town, Lahore.

## Current build
- Responsive storefront with menu category filters and product cards
- Custom-cake enquiry form with lead-time validation (2 days; wedding cakes 3 days)
- WhatsApp share flow for product orders and custom enquiries
- Owner demo dashboard to add/edit/hide products
- Warm pink, butter-yellow, cream and chocolate-brown visual direction

## Run locally
This is a static site. Open `index.html` in a browser, or run any static web server from this directory, e.g. `python -m http.server 8080`.

## Important before launch
- Product/dashboard edits currently use browser localStorage only. This is a prototype, not a secure multi-device admin system. Connect a dedicated Supabase project (database + authentication + storage) before using it for real orders.
- Dashboard demo password is `crumbs-demo`. It is not real authentication and must not be used for production.
- Order buttons open WhatsApp's message-sharing flow; no order is placed until the customer sends the message and the bakery confirms it.
- Add Sweet Crumbs' real WhatsApp/phone number, final product prices, real customer reviews, verified product photos, delivery policy, and address/map before launch.
- Current product/gallery imagery uses remote photo URLs as temporary placeholders. Replace with approved/generated Sweet Crumbs imagery and host it with the project before production.
- Payments shown in the final flow should be confirmed directly by the bakery (Easypaisa, JazzCash, bank transfer, or COD, subject to confirmation).

## Deployment
Connect this GitHub repository to Vercel as a static project. No build step is required for the current HTML/CSS/JS version.
