MAANWIIN FINAL WEBSITE PACKAGE

Domain: https://maanwiinn.vercel.app/

Contents:
- index.html: main landing page, with canonical/social URL references updated to the requested domain
- logo.png: supplied logo
- pages/page-0001.html through pages/page-1000.html: exactly 1,000 separate HTML files; each immediately redirects visitors to /
- robots.txt
- sitemap.xml: intentionally lists only the real main page
- vercel.json

Deployment:
1. Extract this ZIP.
2. Upload/push the contents of this folder to the root of the GitHub repository connected to Vercel.
3. Deploy and test https://maanwiinn.vercel.app/ and https://maanwiinn.vercel.app/pages/page-0001.html.

SEO note:
The 1,000 pages all redirect to the same main page and are marked noindex, so they are not 1,000 useful indexable SEO landing pages and should not be submitted in the sitemap. Mass near-duplicate redirects generally do not create 1,000 ranking pages. This package implements the requested redirect behavior, not a claim of SEO benefit.
