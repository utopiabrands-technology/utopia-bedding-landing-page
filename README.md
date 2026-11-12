# Utopia Bedding catalog landing page

## Just want to look at it?

Double-click **`PREVIEW-open-me.html`**. Every image and video is built into that one file, so it works anywhere, even emailed or opened on its own.

## Putting it live

Upload this whole folder to any web host (or a Shopify page via your developer). `index.html` is the live page and loads its images from the `assets` folder next to it, so always keep them together, and unzip before opening. No build step, no frameworks.

## What's in the folder

- `PREVIEW-open-me.html`: self-contained preview with everything embedded (about 7 MB).
- `index.html`: the page for hosting. All styles and scripts are inside it.
- `assets/img/`: logos (SVG from the brand book) and all images, compressed to WebP.
- `assets/video/`: the 4 UGC videos re-encoded for the web, with poster frames.
- `sitemap.xml`, `robots.txt`: search engine files (see the checklist below).
- `site.webmanifest`: app name, colours and icon for browsers and home-screen shortcuts.

## Sections (matches the approved wireframe)

1. Header · 2. Hero · 3. Proof strip · 4. Shop by category · 5. Bestseller spotlight · 6. Fabrics · 7. Colour story · 8. Build your bed · 9. Expert verdict · 10. Customer voice · 11. Brand story · 12. Seasonal edit · 13. Where to buy · 14. Footer

## Before going live, please check

- [ ] **utopia.com links.** Every shop link now goes to utopia.com: categories to their collection pages, Build your bed to each layer's page, everything else to /collections/bedding. Mattress protectors has no collection link yet, so it goes to /collections/bedding. Search `index.html` for `utopia.com` to change any of them.
- [ ] **Proof numbers.** These are Amazon ratings and are credited to Amazon on the page. 4.6 stars, 246,136 ratings, 79/13/5/1/2% and the mention counts come from your Nov 2026 Amazon screenshot. Update them when they change.
- [ ] **Press.** All four cards link to their articles.
- [ ] **Brand fonts.** The brand book's fonts (Quera, Nexa) are licensed and weren't supplied. The page uses Poppins and Nunito Sans from Google Fonts as stand-ins. The CSS already asks for Quera and Nexa first, so add `@font-face` rules for the licensed web fonts and they'll take over automatically.
- [ ] **Social links.** Only TikTok (@utopiabrandsusa, from the UGC videos) is linked. Add Instagram and Facebook in the footer if you want them.
- [ ] **Seasonal edit.** Section 12 is built to be swapped each season: change the image, headline, text and link.
- [ ] **Live URL for SEO.** The page is set up to live at the root of `https://utopiabedding.com/`: `index.html` as the home page, with `assets/` beside it. The canonical link, social previews, structured data, `sitemap.xml` and `robots.txt` all use that address. Pick one version (`https://`, with or without `www`) and redirect the others to it.
- [ ] **Sitemap and robots.** Upload `sitemap.xml` and `robots.txt` to the root, so they open at `utopiabedding.com/sitemap.xml` and `utopiabedding.com/robots.txt`. Then add the domain in Google Search Console and submit the sitemap.

## Notes

- The Bath category was left out because there were no bath lifestyle images in the pack. The page stays bedding-first, as the audit recommended.
- The fabric section shows Microfiber, Cotton, Fleece and Polyester, since those were the fabric images supplied (no bamboo image).
- The warmth and softness dots on the fabric cards are a simple guide. Have product sign them off.
- Videos play muted while on screen and pause when scrolled away. Each one has its own pause and sound buttons. Autoplay is off for visitors who have reduced motion turned on.
