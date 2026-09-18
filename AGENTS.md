# Repository instructions

This file applies to the entire repository.

Before adding or changing archive content, read and follow `ARCHIVE_RULES.md`. That document is the source of truth for page structure, links, images, SEO metadata, structured data, sitemap updates, and pre-deployment checks.

In particular:

- Preserve existing public URLs unless a migration is explicitly requested.
- Use real `<a href>` links for navigation, downloads, purchases, and Naver source links.
- Give every image descriptive alt text when appropriate, intrinsic dimensions, loading behavior, and async decoding as defined in the rules.
- Keep visible content, pricing, availability, CTA destinations, metadata, and JSON-LD consistent.
- When adding content, update the relevant index and `sitemap-v2.xml` in the same change.
- Do not delete the Google verification file or change site-wide crawling and canonical settings without checking their impact.
- Complete the checklist in `ARCHIVE_RULES.md` before handing off changes.
