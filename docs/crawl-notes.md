# Crawl Notes

Crawl source: `https://bask.health/` public pages.

Fetched successfully:
- `/` homepage HTML metadata/content
- `/plans` pricing HTML metadata/content
- `/sitemap.xml` sitemap index only

Blocked or rate-limited in this environment:
- `/contact` 429
- many deeper routes 403 through Vercel/security protection
- browser session showed Vercel Security Checkpoint failure

Because deeper pages were blocked, the scaffold includes every observed internal route from nav/footer, but pages beyond home/plans are neutral structural placeholders rather than content-derived reconstructions.
