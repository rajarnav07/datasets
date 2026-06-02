# OfficeQA-style headroom task source PDFs

Hosted PDFs for GAIA evaluation tasks (project: Gemini headroom collection on OfficeQA-style enterprise document reasoning).

## Task directories

| Task | Dir | Pages | Notes |
|---|---|---|---|
| BIS Fed swap lines | `BIS_AR/` | 3 × ~100 | digital, multi-doc |
| Treasury 1942 | `Treasury_Bulletin_1942/` | 3 × ~80 | scanned, multi-doc |
| NVDA segments + charts | `NVDA/` | 3 PDFs | digital, chart-heavy |
| BEA GDP Q1 2025 (E1) | `bea_gdp_q1_2025_adv/` | 16 | column-trap + footnote-trap |
| Walmart FY2025 10-K (M1) | `walmart_fy2025_10k/` | 97 | multi-segment arithmetic |
| OECD Czechia 2025 (M2) | `OECD_Czechia_2025_ES/` | 131 | chart-reading parametric interference |
| BEA GDP Q3 2024 cross-edition | `bea_gdp_q3_2024_restated/` | 3 × 2 | superseded |
| Berkshire Hathaway 2024 AR (D1v2) | `berkshire_2024_AR/` | 150 | long-context + competing-value traps |
| **H1 LLNL Sankey 2020/21/22** | `LLNL_energy_flow/` | 3 × 1 | Sankey diagram, energy flow |
| **H2 Transparency CPI 2022/23/24** | `J2H2_heatmaps/` | 22 + 26 + 21 | choropleth color-bin trap |
| **H3 ExxonMobil 4Q24 + 3Q24** | `J2H3_earnings_waterfall/` | 47 + 34 | waterfall earnings bridge |
| **H4 Apple Env Progress 2024 + 2025 (trimmed)** | `J2H4_apple_esg/` | 22 + 20 | stacked bar + donut + unit traps |

All PDFs trimmed to load-bearing pages where applicable. Token-safe (well under Gemini 3.5 Flash's 1,048,576-token input cap).
