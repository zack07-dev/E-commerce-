# VELAMOUR (demo storefront)
Static HTML/CSS/JS. No build step.
**Preview:** open `index.html`, or run `python3 -m http.server` and visit localhost:8000.
**Deploy:** push to GitHub, then Settings > Pages > Deploy from branch `main`, folder `/ (root)`. All paths are relative, so repo subpaths work.
**Configure:** `assets/js/components.js` (`CONFIG`: currency, shipping, discount, email, WhatsApp). Products: `assets/js/products.js`.
**Images:** placeholders are generated SVGs. Add real photos to `assets/images/` and set `images:[...]` on a product.
**Needs an external service (not included):** payments, orders, checkout, email/newsletter, contact form, accounts.
**Not built yet:** categories, about, contact, search, account, checkout, FAQ, shipping, returns, privacy, terms pages; quick view; cookie notice; sitemap.
