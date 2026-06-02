# OfficeQA-style headroom task source PDFs

Hosted PDFs for GAIA evaluation tasks (project: Gemini headroom collection on OfficeQA-style enterprise document reasoning).

## Active June 2 batch (H1-H7)

| Task | Dir | Pages | Theme |
|---|---|---|---|
| H1 | `LLNL_energy_flow/` | 159 | Sankey + EIA/IEA distractors |
| H2 | `J2H2_heatmaps/` | 159 | Transparency CPI choropleths (2019-2024) |
| H3 | `J2H3_earnings_waterfall/` | 154 | ExxonMobil 4Q24+3Q24+2Q24+1Q24 earnings decks |
| H4 | `J2H4_apple_esg/` | 180 | Apple Environmental Progress 2024+2025 |
| H5 | `J2H5_scanned_finance/` | 195 | Federal Reserve Annual Reports 1941+1944 (OCR-fragile) |
| H6 | `J2H6_hard_plots/` | 150 | CDC NVSR Deaths 2021+2022 log-scale plots |
| H7 | `J2H7_legal_regulatory/` | 160 | DOJ Google Adtech + Live Nation antitrust complaints |

## Prior batches

| Dir | Source |
|---|---|
| `BIS_AR/` | BIS Annual Economic Reports 2019/2020/2021 |
| `Treasury_Bulletin_1942/` | US Treasury Bulletin Sept/Oct/Nov 1942 |
| `NVDA/` | NVIDIA FY2024 + FY2023 + AMD FY2023 10-K |
| `bea_gdp_q1_2025_adv/` | BEA GDP Q1 2025 Advance |
| `walmart_fy2025_10k/` | Walmart FY2025 Annual Report |
| `OECD_Czechia_2025_ES/` | OECD Economic Surveys: Czechia 2025 |
| `berkshire_2024_AR/` | Berkshire Hathaway 2024 Annual Report |
| `bea_gdp_q3_2024_restated/` | BEA GDP Q3 2024 (legacy, superseded) |

All PDFs token-safe under Gemini 3.5 Flash's 1,048,576-token input cap.

## june_4 batch (J4A-J4D) — old scanned, dense barely-visible plots, multi-page, no table backup

| Task | Dir | Source | Pages | Plot type |
|---|---|---|---|---|
| J4A | `J4A_statistical_atlas/` | US Statistical Atlas, 1900 Census (Gannett) | 149 | hand-engraved rank-order bar plates (no labels) |
| J4B | `J4B_naca_aero/` | NACA TR-824 Summary of Airfoil Data (1945) | 131 | dense log-log airfoil polars / coefficient curves |
| J4C | `J4C_weather_ag/` | USDA Atlas of American Agriculture — Climate | 60 | hand-drawn isopleth (contour) climate maps |
| J4D | `J4D_usgs_hydro/` | USGS Water-Supply Paper 1543-A (flood-frequency) | 86 | Gumbel / log-log flood-frequency curves (no data tables) |
