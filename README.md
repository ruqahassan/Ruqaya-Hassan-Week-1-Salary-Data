## README

# Week 1 — AI & Data Science Salaries Analysis
**TalentPulse Analytics | Capstone Data Analytics Program**

## Files
| File | Description |
|------|-------------|
| `Week1_YourName.ipynb` | Main notebook (Parts A–E) |
| `cleaned_salaries.csv` | Cleaned, deduplicated dataset with predicted salaries |
| `Week1_Dashboard.pbix` | Power BI interactive dashboard |
| `Dashboard_Screenshots.pdf` | PDF export of dashboard pages |
| `README.md` | This file |

## Reproduction Steps
1. Clone the repository
2. Place `ds_salaries.csv` and `global_tech_salary.csv` in the same directory
3. Run `Week1_YourName.ipynb` top-to-bottom (all cells execute without errors)
4. Open `Week1_Dashboard.pbix` in Power BI Desktop
5. If prompted, re-link data to the local `cleaned_salaries.csv`

## Requirements
Python 3.9+ with: pandas, numpy, matplotlib, seaborn, scipy, scikit-learn

## Key Findings
- Experience level is the #1 salary driver (Entry $64K → Executive $180K median)
- 82% US-centric dataset — non-US estimates carry high uncertainty
- Best model: Gradient Boosting (R² ≈ 0.46, MAE ≈ $35K)
- Salary growth plateaued post-2022; current market is less competitive than 2021 peak

