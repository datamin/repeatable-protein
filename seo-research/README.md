# SEO research

This folder is the source of truth for keyword and SERP research.

## Files

- [`keyword-clusters.csv`](keyword-clusters.csv) — cluster-level opportunity summary for US and India.
- [`keywords.csv`](keywords.csv) — one row per keyword and country.
- [`keyword-research-summary.md`](keyword-research-summary.md) — readable tables, interpretation, and recommended priorities.
- [`serp-notes.md`](serp-notes.md) — competitor, intent, format, and ranking observations.

## Required metrics

- `volume`: estimated monthly searches for the selected country.
- `kd`: keyword difficulty from the recorded SEO data source.
- `intent`: informational, commercial, transactional, or navigational.
- `checked_on`: the date the metric was collected.

Search volumes and KD are directional estimates. Preserve the date and source because tools update their databases over time.

## Research status

The first Semrush pass on 2026-08-30 validates three areas:

1. Eating 100 g of protein per day, especially in the US.
2. High-protein vegetarian meal plans, with stronger demand in the US than India.
3. India-specific searches for the protein in 100 g of individual vegetarian foods.

Protein-without-tracking, eggetarian, breakfast, lunch, busy-women, repeated-meal, and workout clusters still require a complete metric pass.

Do not combine keywords merely because they share words. Group them only when the same page format and answer can satisfy their search intent.
