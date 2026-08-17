# August 2026 Market Report: Lofty Paste Sheet

## SEO fields for the Lofty blog editor

**Blog Post Name**
August 2026 Portland Metro Real Estate Market Update: Sales Up, Showings Down

**Page Slug**
/blog/august-2026-portland-metro-real-estate-market-update

**Meta Title** (71 chars)
August 2026 Portland Metro Housing Market Update: Sales Up, Prices Flat

**Meta Description** (154 chars)
Portland Metro closed 2,167 homes in July 2026, up 8.1% year over year, while the median price held at $555,000. See what it means for buyers and sellers.

**Meta Keywords**
Portland metro real estate; Portland housing market 2026; August 2026 market update; Portland home prices July 2026; Beaverton Aloha home prices; Lake Oswego West Linn median price; Hillsboro Forest Grove housing market; Portland mortgage rates August 2026; Is August 2026 a good time to buy a home in Portland; Will Portland home prices drop in 2026; Portland inventory in months; Portland seller strategy 2026

**Blog Categories**
Market Update; Portland Metro; Buyer Resources; Seller Resources

---

## Schema (separate field)

Lofty now takes schema in its own JSON block rather than inside the post body. Two files cover both cases:

- **august-2026-schema.json** — bare JSON. Use this if the Lofty field expects the object only. Most CMS schema fields do.
- **august-2026-schema-script-tag.html** — same JSON wrapped in `<script type="application/ld+json">`. Use this only if the field expects a full script tag.

Paste one or the other, never both. If you are not sure which the field wants, paste the bare JSON first and check the rendered page source: it should show exactly one `<script type="application/ld+json">` block. Two script tags, or a script tag nested inside another, will make Google skip the markup.

The blog HTML in this folder already has the schema stripped out, so pasting the body and the schema field will not double up.

---

## Before you publish

The HTML already points at the GitHub Pages URLs it will need. Nothing to find and replace, but the five files have to exist first.

Upload to `joe-exprlty/sellingpdxhomes-images/market-reports/august-2026/` with these exact names:

| File | Used for |
|---|---|
| hero.webp | Hero image, top of post |
| market-context.webp | After Market Overview |
| buyer-scene.webp | Affordability section |
| metro-area.webp | Before the sub-market table |
| sns.webp | Open Graph social card, not embedded in the body |

Marblism prompts for all five are in the Phase 1 package.

---

## What is in the post

- 1,799 visible words, 1,200 behind expanders, 2,999 total
- 9 expand bars, every one with a data teaser for AI crawlers
- 5 tables: sub-market spotlight (5 visible, 10 behind), inventory in months (2026 visible, 3-year behind), price distribution (behind an expander)
- 3 CTA boxes at the end of each act
- 8 FAQ questions, answers 41 to 48 words, matching the FAQPage schema word for word
- 9 internal links, 11 external, Realtor.com used only as Tier 3 corroboration
- No Insight block. Send me a field observation and I will add one.

---

## Two things to know about the numbers

**The +8.1% headline uses the RMLS published figure.** RMLS restates prior-year closings as late sales report in. Against the restated July 2025 count of 2,080 the gain is +4.2%. The post uses RMLS's own +8.1% and never mixes the two tables in a single comparison.

**Sub-market medians are year to date.** That is the only median RMLS publishes at the area level. The post says so above the table.

---

## After it goes live

1. Ask an AI a question the post answers, without giving it the link, and see whether it cites you. Good test: "Why did Portland closed sales rise while showings fell in July 2026?"
2. Give an AI the URL and ask what it can and cannot see. Compare against what is behind the expanders.
3. Note any visual issues: table banding, expand bar colors, anything that reads differently live than expected.
