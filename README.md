# Amazon FBA Fee Rates 2026 (Open Dataset)

Versioned, machine-readable Amazon FBA fee schedules for 2026, published by
**[ylishi.tools](https://ylishi.tools)** — US and EU/UK marketplaces.

- **Dataset page, methodology & citation format**: https://ylishi.tools/rates/
- **Zenodo DOI (always resolves to latest)**: https://doi.org/10.5281/zenodo.23409316
- **License**: [CC BY 4.0](LICENSE) — use freely, attribute "Data: ylishi.tools (https://ylishi.tools/rates/), CC BY 4.0"

## Files

| File | Contents |
|------|----------|
| `fba-us-2026.json` | US: referral fees by category, FBA fulfillment by size tier, monthly/peak storage, aged inventory surcharge, inbound placement, low-inventory-level fee, return processing, 2026-10-15 peak fulfilment uplift, 3.5% fuel surcharge |
| `fba-eu-2026.json` | EU/UK: fulfillment fees, storage (GBP/cu-ft, EUR+SEK/cu-m), 1.5% EU fuel surcharge, 2026 EU cross-border import charges (EUR 3 statutory duty ≤EUR 150, EUR 2 Union handling fee) |
| `snapshots/2026-*.json` | Frozen monthly snapshots — each month's exact numbers |
| `snapshots/index.json` | Snapshot registry |

Each file carries a `dataset` header with `version`, `last_verified`,
`effective_dates`, `sources` (official Amazon Seller Central references) and a
`worked_example` reproducibility check.

This repo is a convenience mirror; the canonical JSON is served from
https://ylishi.tools/rates/ and archived on Zenodo with a citable DOI.
