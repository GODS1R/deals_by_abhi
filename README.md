# Deals by Abhi

A single-page site for sourcing buyer interest before stock is purchased. Drives traffic from Facebook Marketplace listings.

## Enable GitHub Pages

1. Go to the repo on GitHub → **Settings** → **Pages**
2. Under "Build and deployment", set **Source** to **Deploy from a branch**
3. Choose branch `main`, folder `/ (root)`, then **Save**
4. Your site will be live at `https://<your-username>.github.io/deals_by_abhi/` within a minute or two

## Updating product cards

All content lives in `index.html`. Each product is a `.product-card` block inside the `<section id="listings">` section, marked with a comment.

To add/edit a product, copy a `.product-card` block and update:

- `<h3>` — product name
- badge class: `sealed`, `openbox`, or `used` (controls color), and its text
- `.price` — price
- `.availability` — availability date text
- `.interest-count` — interested count text (update manually as people register)
- `.btn href` — link to your Google Form or WhatsApp (`https://wa.me/<number>`)

## Updating placeholder links

Search `index.html` for `href="#"` and replace with:

- The **"I'm Interested"** buttons → your Google Form link or `wa.me` WhatsApp link
- The **"Fill Out Interest Form"** button → your Google Form link
- The **footer Facebook link** → your Facebook Marketplace profile URL
