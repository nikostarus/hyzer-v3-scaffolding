# Crawl Notes

Crawl source: archived internal reference crawl from setup phase.

Fetched successfully:
- `/` homepage HTML metadata/content
- `/plans` access-track HTML metadata/content
- `/sitemap.xml` sitemap index only

Blocked or rate-limited in this environment:
- `/contact` 429
- many deeper routes 403 through Vercel/security protection
- browser session showed Vercel Security Checkpoint failure

Because deeper pages were blocked, the site includes every observed internal route from nav/footer, but pages beyond home/plans are neutral coming-soon module pages rather than content-derived reconstructions.
