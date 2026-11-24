# EcoGrid Website

A responsive React + Vite front-end prototype based on the EcoGrid activity report.

## Run locally
1. Install Node.js (18 or newer).
2. Extract this ZIP and open the `ecogrid-website` folder in VS Code.
3. Open the VS Code terminal in this folder.
4. Run:

```bash
npm install
npm run dev
```

5. Open the local URL printed by Vite (usually http://localhost:5173).

## Included screens
- Executive dashboard with KPI cards, energy trend, consumer mix, zone overview, alerts and 7 × 24 demand heatmap.
- Analytics charts.
- Query Performance Laboratory (clearly labelled illustrative demo metrics).
- CSV upload and browser-side preview.
- Smart meter directory with search, add, edit, delete and CSV export.
- Readings explorer with quality filters.
- ETL cleaning demonstration with configurable MAD threshold.

## Important integration note
This is a working front-end prototype with sample data. It does not yet connect to a MongoDB database, Node.js/Express API or Python ETL process. The query benchmark and ETL report are illustrative. To make it a fully data-backed project, connect the UI to the backend endpoints and real `explain("executionStats")` and Pandas ETL outputs described in the report.
