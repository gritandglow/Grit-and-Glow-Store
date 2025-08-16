
# Grit & Glow — Free Static Storefront (GitHub Pages + Payhip)

**What this is:** A zero-cost storefront that lists your products and sends buyers to Payhip for checkout & file delivery.

## Launch in ~10 minutes
1) Create a new public GitHub repo (e.g., `grit-and-glow-store`).
2) Upload all files from this folder.
3) In repo **Settings → Pages**, set Source to "Deploy from a branch", select `main`, folder `/root`, and Save.
4) Your site appears at `https://<username>.github.io/grit-and-glow-store`.
5) Edit `products.json` with your product(s) and real Payhip URLs.
6) Replace `assets/hero-placeholder.png` with your mockups.

## Add more products
Duplicate the object in `products.json`. Fields:
- `title`, `sku`, `price`, `summary`, `description`, `images` (array), `payhip_url`, `tags` (array), `files_included`, `license`

## Notes
- Payment processing fees still apply on Payhip/PayPal.
- For a custom domain later: buy a domain and add GitHub Pages DNS (optional).

— Enjoy!
