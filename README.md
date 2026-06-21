# rg-history
Visualization dashboard for RG History of Products

A single-page (`index.html`) interactive timeline of Redgate's products, bundles, and pivots. Horizontal scroll on wide screens, vertical layout on portrait/narrow monitors, with light/dark themes and a "Save as PDF" export.

## Data files & refresh cadence

The dashboard content is hand-curated from these point-in-time snapshots — **not** a live feed:

| File | Source | Refresh cadence |
| --- | --- | --- |
| `products.md` | red-gate.com/products | Every 6 months / on major launch or retirement |
| `bundle-history.md` | documentation.red-gate.com bundle history | Every 6 months / on bundle change |
| `Redgate_Software_Editions.md` | red-gate.com software editions | Every 6 months / on edition or pricing change |

When you refresh a snapshot, bump its "Retrieved/Last updated" date, update the **"Data current as of …"** label in `index.html` (search `site-foot`), and commit. For current pricing and product details, always defer to [red-gate.com](https://www.red-gate.com/products/).
