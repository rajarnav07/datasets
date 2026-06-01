# OfficeQA-style headroom task source PDFs

Hosted PDFs for GAIA evaluation tasks (project: Gemini headroom collection on OfficeQA-style enterprise document reasoning).

## Task PDFs

| Task | Slot | Source | Pages | Notes |
|---|---|---|---|---|
| BIS Fed swap lines | `BIS_AR/` | BIS Annual Economic Reports 2019/2020/2021 | 94 + 118 + 118 | digital, multi-doc |
| Treasury 1942 | `Treasury_Bulletin_1942/` | US Treasury Bulletin Sept/Oct/Nov 1942 (FRASER scan) | ~80 each | scanned, multi-doc |
| NVDA segments + charts | `NVDA/` | NVIDIA FY2024 AR + FY2023 AR + AMD FY2023 10-K | 187 + 268 + ~120 | digital, chart-heavy |
| BEA GDP Q1 2025 (E1, easy) | `bea_gdp_q1_2025_adv/` | BEA "GDP, 1st Quarter 2025 (Advance Estimate)" Apr 30 2025; Table 7 removed to force derivation through Table 3 | 16 pp | digital, column-trap + footnote-trap |
| Walmart FY2025 10-K (M1, medium) | `walmart_fy2025_10k/` | Walmart FY2025 (year ended Jan 31, 2025) Annual Report — Note 12 Segments trimmed | 15 pp | digital, multi-segment arithmetic |
| OECD Czechia 2025 (M2, chart-reading) | `OECD_Czechia_2025_ES/` | OECD Economic Surveys: Czechia 2025 (Mar 2025) — Executive Summary trimmed | 11 pp | chart-heavy, parametric-interference vector |
| BEA GDP Q3 2024 cross-edition (D1, difficult) | `bea_gdp_q3_2024_restated/` | BEA "GDP Q3 2024" Advance (Oct 2024) + Second (Nov 2024) + Third (Dec 2024) | 2 + 2 + 2 = 6 pp | digital, restated-figure, UID0019 archetype |

All PDFs trimmed to load-bearing pages only, well under Gemini 3.5 Flash's 1,048,576-token input cap.
