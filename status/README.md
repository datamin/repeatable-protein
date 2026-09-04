# Publication status

This folder will track published URLs and search performance after the website is live.

## Files

- [`page-status.md`](page-status.md) — human-readable dashboard combining live URLs, planned pages, target clusters, Semrush volume/KD, SERP-review status, and future GSC fields.
- [`published-pages.csv`](published-pages.csv) — publication, indexing, update, and performance history.

## Reporting convention

- Use Google Search Console as the source for clicks, impressions, CTR, and average position.
- Record the comparison window for every snapshot.
- Do not overwrite historical measurements; append a new row for a new reporting date.
- Page status values: `draft`, `published`, `indexed`, `needs_update`, `consolidate`, or `retire`.

The current published-page dashboard is maintained in [`page-status.md`](page-status.md).
