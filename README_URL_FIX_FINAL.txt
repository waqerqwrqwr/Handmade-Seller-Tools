Simple Tool Works — URL / Canonical Fix Pack — 2026-10-07

UPLOAD / REPLACE THESE FILES:
about.html
contact.html
demo.html
privacy.html
pro-excel.html
terms.html
product.html
sitemap.xml
blog/index.html
blog/how-to-price-handmade-products.html
blog/real-profit-handmade-product.html
blog/handmade-pricing-mistakes.html

URL RULE:
Public/canonical URLs use NO .html extension.
The GitHub filenames remain .html; this is intentional.

Examples:
/demo
/product
/pro-excel
/about
/contact
/privacy
/terms
/etsy-profit-calculator
/blog/how-to-price-handmade-products

IMPORTANT:
index.html and the calculator pages that already use no-extension canonical URLs were not overwritten in this pack to avoid regressing newer content.

ONE EXISTING GUIDE NOTE:
/guides/how-to-calculate-etsy-profit is already using the correct canonical URL. Its old footer contains links ending in .html. Replace only these four footer targets in that existing file:
/about.html -> /about
/contact.html -> /contact
/privacy.html -> /privacy
/terms.html -> /terms

After upload:
1. Wait for Cloudflare deployment.
2. Open https://simpletoolworks.com/sitemap.xml and confirm it loads.
3. In Search Console, submit the FULL sitemap URL: https://simpletoolworks.com/sitemap.xml
4. Test https://simpletoolworks.com/demo (not demo.html) with URL Inspection.
5. Then validate the redirect-error fix.
