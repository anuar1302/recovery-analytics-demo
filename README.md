# Recovery analytics — one source of truth (demo)

Live: https://anuar1302.github.io/recovery-analytics-demo/

A single-file demo of how I build analytics for a collections / recovery business:

- KPI tiles, charts, invoices and the reconciliation gate all read from one metric layer
- reconciliation gate: pipeline vs payments ledger; a mismatch blocks publishing
- A/B readout with a two-proportion z-test and a 95% CI
- automated per-lender invoicing in local currency → USD, CSV export

All data is randomly generated with a fixed seed. Lender names are fictional; nothing here describes a real company or person.

Plain HTML + JS, no build step, no dependencies.
