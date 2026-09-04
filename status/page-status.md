# SEO page status

Last updated: 2026-09-04

This is the human-readable dashboard for page publication, target keywords, keyword opportunity, SERP research, and future Google Search Console performance. The CSV files remain the source for row-level history.

## Published pages

| ID | Page | Live URL | Status | Market | Target cluster | Primary keyword | Primary keyword volume | Selected cluster volume | Representative KD | SERP review | Indexed | GSC period | Impressions | Clicks | CTR | Average position |
|---|---|---|---|---|---|---|---:|---:|---:|---|---|---|---:|---:|---:|---:|
| H001 | Strong on Repeat home | [Live page](https://strongonrepeat.com/) | Published | US + India | Brand and personal story | — | — | — | — | Not applicable | Pending | — | — | — | — | — |
| P001 | How I Aim for 100g of Protein Without Tracking Every Meal | [Live page](https://strongonrepeat.com/100g-protein-without-tracking/) | Published | US primary; India secondary | C01 · 100g protein per day; C02 · protein without tracking | how to get 100g of protein a day | 1,000 | 7,420 | 38 | Partial; full top-result review pending | Pending | — | — | — | — | — |
| P002 | High-Protein Vegetarian Meal Plan: A Repeatable 100g Day | [Live page](https://strongonrepeat.com/high-protein-vegetarian-meal-plan/) | Published | US primary; India secondary | C03 · high-protein vegetarian meal plan | high protein vegetarian meal plan | 320 | 890 | 23 | Intent checked; full top-result review pending | Pending | — | — | — | — | — |
| T001 | About Priyanka | [Live page](https://strongonrepeat.com/about/) | Published | Global | Trust and author information | — | — | — | — | Not applicable | Pending | — | — | — | — | — |
| T002 | Editorial methodology | [Live page](https://strongonrepeat.com/editorial-methodology/) | Published | Global | Trust and methodology | — | — | — | — | Not applicable | Pending | — | — | — | — | — |

## Planned SEO pages

Planned URLs are working slugs and will not resolve until the page is published.

| ID | Planned page | Working slug | Status | Market | Target cluster | Primary keyword | Primary keyword volume | Selected cluster volume | Representative KD | SERP review | Priority |
|---|---|---|---|---|---|---|---:|---:|---:|---|---|
| P003 | 100g Protein Indian Diet: Vegetarian and Egg Options | `/100g-protein-indian-diet/` | Keyword validated | India | C01; C03; C04 | 100g protein diet | 480 | 540 | 27 | Intent checked; full review pending | High |
| P004 | High-Protein Vegetarian Breakfasts to Repeat All Week | `/high-protein-vegetarian-breakfast/` | Research pending | US + India | C05 | high protein vegetarian breakfast | — | — | — | Pending | High |
| P005 | High-Protein Vegetarian Lunches for Work and Meal Prep | `/high-protein-vegetarian-lunch/` | Research pending | US + India | C06 | high protein vegetarian lunch | — | — | — | Pending | High |
| P006 | Build Your Repeatable Protein Day | `/protein-day-planner/` | Research pending | Global | C01; C02 | protein meal planner | — | — | — | Pending | High |
| P007 | Is It Healthy to Eat the Same Breakfast and Lunch Every Day? | `/same-breakfast-and-lunch-every-day/` | Research pending | Global | C08 | eating the same breakfast every day | — | — | — | Pending | Medium |
| P008 | 30-Minute Strength Training Three Times a Week | `/30-minute-strength-workout-3-days-a-week/` | Research pending | Global | C09 | 30 minute strength workout 3 days a week | — | — | — | Pending; qualified review also required | Low |
| P009 | Protein per 100g of Vegetarian Foods | `/protein-per-100g-vegetarian-foods/` | Keyword validated | India | C10 | paneer protein per 100g | 40,500 | 185,900 | 17 | Intent checked; full review pending | High |
| P010 | High-Protein Indian Vegetarian Breakfasts for Busy Women | `/high-protein-indian-vegetarian-breakfast/` | Research pending | India + Indian women in US | C05 | high protein Indian vegetarian breakfast | — | — | — | Pending | High |
| P011 | High-Protein Indian Lunch and Tiffin Ideas for Work | `/high-protein-indian-lunch-for-work/` | Research pending | India + Indian women in US | C06 | high protein Indian lunch | — | — | — | Pending | High |
| P012 | 100g Protein Indian Vegetarian Meal Plan for Women | `/100g-protein-indian-vegetarian-meal-plan-for-women/` | Consolidation decision pending | India + Indian women in US | C01; C03; C04 | 100g protein Indian vegetarian diet | — | C01: 540; C03: 210 | C01: 27; C03: 32 | Pending; check overlap with P003 | High |
| P013 | Indian Grocery List for a Repeatable High-Protein Week | `/indian-high-protein-grocery-list/` | Research pending | India + Indian women in US | C03; C05; C06 | high protein vegetarian grocery list | — | 210 partial | 32 partial | Pending | Medium |

## Metric definitions

- **Primary keyword volume** is the estimated monthly Semrush search volume for the exact target phrase in the stated market.
- **Selected cluster volume** is the sum of the keyword variants retained in the research file. Variants may overlap, so it is an opportunity indicator—not a traffic forecast.
- **Representative KD** is Semrush keyword difficulty for the representative cluster keyword, not a guarantee of how difficult our specific page will be to rank.
- `—` means the metric has not been researched or does not apply; it does not mean zero.
- Current keyword figures come from Semrush Keyword Magic Tool research checked on 2026-08-30.
- GSC fields remain blank until Search Console is connected and begins reporting data.

## Update process

1. Update publication and keyword targeting here when a page is created or materially repositioned.
2. Append dated measurements to `published-pages.csv`; do not replace earlier GSC snapshots.
3. Copy the latest GSC period, impressions, clicks, CTR, average position, indexing state, and leading query into the published-page table.
4. Refresh keyword metrics with a new checked date instead of silently replacing their source or market.
