# Your Shop Name Here — storefront template

Static, dependency-free, single-page dispensary storefront. Deploy `dist/` to any static host (Vercel, Netlify, Cloudflare Pages).

## Before launch
1. Find/replace "Your Shop Name Here", the address, phone, license number (C10-0000000-LIC) and yourshopnamehere.com.
2. Replace the `P` product array in index.html with your POS/menu feed (Dutchie, Jane, Treez, Blaze, etc.).
3. Swap the browser-local auth (search "Auth (template") for your provider (Supabase, Clerk, Auth0, Firebase). Never ship localStorage accounts.
4. Point the checkout `checkout()` function at your order/reservation API.
5. Set the real delivery ZIP list in the "Delivery ZIP" block and confirm tax rates (EXCISE, SALES) for your city.
6. Add og-image.jpg (1200×630) and your own legal pages.

## Compliance notes
- 21+ age gate on entry and DOB check at registration; ID still verified at pickup/delivery.
- Daily purchase limits enforced in cart (28.5g flower / 8g concentrate, CA defaults).
- No health claims in copy. Review all copy against your state's advertising rules.
- Many ad networks prohibit cannabis ads; plan traffic around SEO, Google Business Profile, Leafly/Weedmaps listings and email/SMS.
