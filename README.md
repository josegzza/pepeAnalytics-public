# pepeAnalytics — MLB Picks Tracker

Public performance dashboard for pepeAnalytics daily picks.

- **1 flat unit** per pick.
- **Top-5 best value** picks published every day on X — [@pepeAnalytics](https://x.com/pepeAnalytics).
- Results settled automatically the following day.

## Disclaimer

This dashboard is for informational and performance tracking purposes only.
It does not constitute financial advice or a recommendation to bet. Gamble
responsibly, within your means, and only where it is legal in your jurisdiction.

## Structure

- `index.html` — dashboard (vanilla JS + ApexCharts).
- `data/picks.json` — full history of settled picks.
- `data/summary.json` — precomputed KPIs (record, ROI, equity curve).

Data is updated automatically every morning ET via a push from the private repo.
