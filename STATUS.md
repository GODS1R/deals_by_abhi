# Deals by Abhi — Project Status

## What This Is
A GitHub Pages product catalog site for a product flipping business (Kitchener, ON).
- Source products from auction (encoreauctions.hibid.com)
- Sell via Facebook Marketplace
- Site URL: https://gods1r.github.io/deals_by_abhi/

---

## Site Tech Stack
- Single file: `index.html` — pure HTML + CSS, no frameworks
- Images: `img/` folder (23 PNG files, kept for next batch)
- GitHub Pages: Deploy from branch (`main`), `.nojekyll` file present
- Git branches: `main` (live) + `claude/peaceful-volta-4g0cvp` (dev, always kept in sync)

---

## Current Site State
**Products: REMOVED — showing "New Items Listing Soon" page**

The site currently shows:
- Header: "Deals by Abhi | Open box & sealed products" with chips (Sealed, Open Box, ★★★★★ FB Marketplace)
- Big centered "New Items Listing Soon" message with FB messenger button
- FAQ section (condition, warranty, location, pickup, pricing)
- Footer: link to FB Marketplace profile

The product cards were cleared intentionally — waiting for new auction batch.

---

## Facebook Info
- FB Profile: https://www.facebook.com/abhinav.anil.385804/
- FB Marketplace Profile: https://www.facebook.com/marketplace/profile/61556961163312/
- Messenger deep link format: `https://m.me/abhinav.anil.385804?text=URL_ENCODED_MESSAGE`

---

## Enquiry Tracker (Current Interested Buyers)

| # | Name | Product | Their Ask | Notes |
|---|------|---------|-----------|-------|
| 1 | Cole | Alienware Monitor | FB listed price | No negotiation |
| 2 | Braulio | L40 Ultra Gen 2 | — | Enquiry only |
| 3 | Mina | E40 Ultra | ~$180 | Very low, unlikely |
| 4 | Steven | Dreame D20 Air Plus | $150 | Specific ask |
| 5 | Akash | L40S AE | — | Enquiry only |
| 6 | Meera | Dreame D20 Plus | — | Enquiry only |
| 7 | Anand | BL660C + BL780 | — | Both blenders, no price |
| 8 | May | L40 Ultra Gen 2 | — | Enquiry only |
| 9 | Elle | L40 Ultra Gen 2 | ~$380 ($350–$450 budget) | Strong buyer |
| 10 | Nana | Ninja All-In-One Blender | — | Enquiry only |
| 11 | Daryl | BL660C Blender | $50 | Very low ask |
| 12 | (Chinese name) | Dreame D20 Air Plus | — | No price |
| 13 | Okey | Ninja All-In-One Blender | — | Interested |
| 14 | Ale | BL660C Blender | — | Enquiry only |
| 15 | Seyma | Ninja Crispi Air Fryer | — | Enquiry only |

---

## Price Reference (50–70% of Amazon CA Retail)

| Product | Amazon CA | 50% Min | 70% Max | FB Listed | Notes |
|---------|-----------|---------|---------|-----------|-------|
| Dreame D20 Plus | $399 | $200 | $279 | — | |
| Dreame D20 Air Plus (White) | $449 | $225 | $314 | — | Steven at $150 is below min |
| Dreame D20 Air Plus (Black) | $449 | $225 | $314 | — | |
| Dreame L40 Ultra Gen 2 | $899 | $450 | $629 | — | 3 buyers; Elle $350–$450 |
| Dreame L40s Ultra AE | $799 | $400 | $559 | — | |
| Dreame X60 Ultra | $1299 | $650 | $909 | — | |
| MOVA E40 Ultra | $499 | $250 | $349 | — | Mina at $180 is below min |
| MOVA P10 Pro Ultra | $599 | $300 | $419 | — | |
| Shark Vertex Pro IZ662H | $349 | $175 | $244 | CA$199 active | |
| Shark PowerDetect IP1251C | $399 | $200 | $279 | CA$429 active | ABOVE retail — watch this |
| Shark Matrix RV2305CA | $599 | $300 | $419 | — | |
| Ninja BL780C All-in-One | $199 | $100 | $139 | — | |
| Ninja BL660C Blender | $99 | $50 | $69 | — | 3 buyers; Daryl at $50 = min |
| Ninja Pro Plus Food Processor | $149 | $75 | $104 | — | |
| Ninja Crispi Air Fryer | $179 | $90 | $125 | — | Seyma enquired |
| Ninja AF141C Air Fryer 5QT | $129 | $65 | $90 | — | |
| Ninja AF161C Air Fryer XL | $149 | $75 | $104 | — | |
| Ninja AF100C Air Fryer 4QT | $99 | $50 | $69 | — | |
| Ninja BN400C Nutri Blender | $79 | $40 | $55 | — | |
| Logitech MX Keys S | $129 | $65 | $90 | — | |
| Alienware AW2725DF 27" | $999 | $500 | $699 | — | Cole interested |
| Samsung 27" FHD Monitor | $229 | $115 | $160 | — | |

---

## Bidding Priority (Based on Demand)
1. **Dreame L40 Ultra Gen 2** — 3 buyers. Elle's $350–$450 budget = bid ceiling ~$450
2. **Ninja BL660C Blender** — 3 buyers. Daryl at $50 is floor, Anand no price given
3. **Dreame D20 Air Plus** — 2 buyers. Steven at $150 is below viable floor ($225)
4. **Ninja All-In-One BL780C** — 2 buyers (Nana, Okey)
5. **Alienware Monitor** — Cole ready at FB listed price, no negotiation needed
6. **Ninja Crispi Air Fryer** — Seyma enquired
7. **MOVA E40 Ultra** — Mina at $180 is very low (floor is $250)

---

## Files in Repo
```
index.html          — main site file
enquiries.csv       — buyer tracker + price comparison spreadsheet
img/                — 23 product PNGs (kept, reusable for next batch)
.nojekyll           — stops GitHub Pages from running Jekyll
STATUS.md           — this file
```

---

## Next Steps (To Plan)
- [ ] Bid on new auction batch — use enquiry demand to prioritize lots
- [ ] Once items confirmed, add products back to site with images + messenger buttons
- [ ] Decide whether to show price ranges on site or keep "Contact for pricing"
- [ ] Follow up with all enquirers by Monday with confirmed availability
- [ ] Shark PowerDetect ($429 FB listing) is above Amazon retail ($399) — reconsider pricing
