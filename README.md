# Deals by Abhi

A single-page catalog site listing current stock. Buyers contact via Facebook Marketplace for pricing — the site itself doesn't capture leads or show prices.

## Enable GitHub Pages

1. Go to the repo on GitHub → **Settings** → **Pages**
2. Under "Build and deployment", set **Source** to **Deploy from a branch**
3. Choose branch `main`, folder `/ (root)`, then **Save**
4. Your site will be live at `https://<your-username>.github.io/deals_by_abhi/` within a minute or two

## Updating product cards

All content lives in `index.html`. Each product is a `.product-card` block inside the `<section id="listings">` section, marked with a comment.

To add/edit a product, copy a `.product-card` block and update:

- `<h3>` — product name
- badge class: `sealed`, `openbox`, or `used` (controls color), and its label text

## Updating the footer link

Replace `href="#"` on the footer's Facebook link with your Facebook Marketplace profile URL.
