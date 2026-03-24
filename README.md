## 📊 [View Full Report](https://noah-hebert.github.io/macroeconomic-analysis-r-sql/EDA%20project.html)
# macroeconomic-analysis-r-sql
# Macroeconomic Trend Analysis | R + SQL

**Tools:** R · ggplot2 · dplyr · SQLite · Quarto  
**Period:** April 2025 – February 2026  

## Overview
Built a macroeconomic analysis pipeline to model an 11-month 
disinflation cycle. Analyzed inflation, unemployment, GDP growth, 
interest rates, and consumer sentiment using tidyverse wrangling, 
ggplot2 visualization, and SQLite window functions.

## Key Results
| Metric | Change |
|---|---|
| Inflation | −1.1 pp (3.8% → 2.7%) |
| Unemployment | +0.5 pp (4.0% → 4.5%) |
| GDP Growth | −0.9 pp (2.4% → 1.5%) |
| Rate Cuts Modeled | 125 bps |
| Inflation/Unemployment Correlation | −0.9851 |

## Techniques Used
- tidyr `pivot_longer()` for multi-series visualization prep
- SQL window functions: `AVG() OVER`, `LAG() OVER`
- `CASE WHEN` macro regime classification
- Pearson correlation computed natively in SQL
- Quarto for reproducible report rendering

## Files
- `EDA_project.qmd` — full source code
- `EDA_project.docx` — rendered report
