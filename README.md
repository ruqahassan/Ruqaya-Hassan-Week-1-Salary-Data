## README

# Week 1 — Salaries Analysis
**TalentPulse Analytics | Capstone Data Analytics Program**

## Files
| File | Description |
|------|-------------|
| `Week1_Ruqaya.ipynb` | Main notebook (Parts A–E) |
| `cleaned_salaries.csv` | Cleaned, deduplicated dataset with predicted salaries |
| `Week1_Dashboard.pbix` | Power BI interactive dashboard |
| `Dashboard_Screenshots.pdf` | PDF export of dashboard pages |
| `README.md` | This file |

## Reproduction Steps
1. Imported necessary libraries
2. Loaded datasets
3. Cleaned and filtered datasets of missing and duplicate rows
4. Prepared visualizations and code for business analytical questions
5. Developed predictive models
6. Visualized data using PowerBI

## Requirements
Python 3.9+ with: pandas, numpy, matplotlib, seaborn, scipy, scikit-learn

## Key Findings
- Experience level is the #1 salary driver (Entry $64K → Executive $180K median)
- 82% US-centric dataset — non-US estimates carry high uncertainty
- Best model: Gradient Boosting (R² ≈ 0.46, MAE ≈ $35K)
- Salary growth plateaued post-2022; current market is less competitive than 2021 peak

