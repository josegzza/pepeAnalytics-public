# pepeAnalytics — MLB picks tracker

Dashboard público de performance de las picks diarias de pepeAnalytics.

- **1 unidad flat** por pick.
- **Top-5 mejor valor** publicado cada día en X.
- Resultados settleados automáticamente al día siguiente.

## Disclaimer

Este dashboard es solo para fines informativos y de tracking de performance.
No constituye asesoría financiera ni recomendación de apuestas. Apuesta
responsablemente, dentro de tus posibilidades, y solo donde sea legal en tu
jurisdicción.

## Estructura

- `index.html` — dashboard (vanilla JS + Chart.js).
- `data/picks.json` — histórico de picks settleadas.
- `data/summary.json` — KPIs precomputados (record, ROI, equity curve).

Los datos se actualizan automáticamente cada mañana ET vía un push desde el
repo privado.
