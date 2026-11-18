# Multi-Factor Asset Pricing

> Class Project · Linear Econometrics (BU.232.620), Johns Hopkins Carey Business School

Tests the CAPM and the Fama–French three-factor model on the 25 size–book-to-market portfolios, using data from Kenneth French's data library.

## What It Does

**Project 3 — Fama–French three-factor model** (`Project_3_Chengxiang Zhang.ipynb`)
- Runs FF3 regressions (Mkt-RF, SMB, HML) on the 25 size–B/M portfolios.
- Wald test of SMB = HML = 0 — a direct test of CAPM against the three-factor model.
- Robustness checks on the 25 size–operating-profitability and 25 size–investment portfolios.

**Project 2 — CAPM** (`Project_2_Chengxiang Zhang.ipynb`)
- Runs CAPM regressions on the same 25 size–B/M portfolios, the baseline the three-factor model is tested against.

## Tech Stack

Python · Jupyter Notebook · pandas · statsmodels

## How to Run

```bash
jupyter notebook "Project_3_Chengxiang Zhang.ipynb"
```

The notebooks load the CSV files by filename, so keep the data files in the same folder.

## Files

| File | What it is |
| --- | --- |
| `Project_3_Chengxiang Zhang.ipynb` | FF3 regressions, Wald test, robustness checks |
| `Project_2_Chengxiang Zhang.ipynb` | CAPM regressions on the 25 portfolios |
| `25_Portfolios_5x5.csv` | 25 size–B/M portfolios (Ken French data library) |
| `25_Portfolios_ME_OP_5x5.csv` | 25 size–OP portfolios |
| `25_Portfolios_ME_INV_5x5.csv` | 25 size–INV portfolios |
| `F-F_Research_Data_Factors.csv` | Fama–French research data factors |
| `Report.pdf` | Written report for Project 3 |
| `Project 2 Report - Chengxiang.pdf` | Written report for Project 2 |

## Data Note

All portfolio and factor data come from Kenneth French's public data library.
