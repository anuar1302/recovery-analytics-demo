# RecoveryLab — analytics for leadership (demo)

Live: https://anuar1302.github.io/recovery-analytics-demo/

A leadership dashboard for an AI debt-recovery business, in one HTML file:

1. **Portfolio** — accounts in work per market, new vs carried over
2. **Contacts** — promises to pay, kept vs broken; month × channel pivot with CSV export
3. **Collections** — gross / net of fees, payments, accounts, AI conversations vs human escalations, paying debtors
4. **Clients** — top-10 ranking with size tiers, monthly bars and a drill-down card (collections, quality, speed, portfolio)
5. **Debt segments** — ranking with the clients behind each segment
6. **Portfolio health** — month picker, KPI tiles, tables by client / segment / market
7. **Funnel** — five steps from placement to settled, by channel, and channel dynamics with a summary table
8. **AI vs human** — collections, recovery rate and cost per $1 by segment

Every block has a "How it's calculated" note. Nightly data checks (sidebar) block publishing when the pipeline and the payments ledger disagree. Three themes, TV mode, phone layout.

All data is randomly generated with a fixed seed. Clients, markets and segments are fictional; nothing here describes a real company or person.

Plain HTML + JS, no build step, no dependencies.
