# AFM 244 – Quiz 2: Industry Analysis Dataset

## Overview
This notebook is part of coursework for **AFM 244 (Data Analytics)** at the University of Waterloo. It loads and previews a firm-year financial fundamentals dataset covering fiscal years **2000–2022**, structured in a Compustat-style format.

## Contents
- `AFM244_QUIZ2.ipynb` — Jupyter/Colab notebook

## What the notebook does
1. Imports `pandas` and `numpy`.
2. Loads `industryAnalysis_2000_2022.csv` into a DataFrame (`industry_csv`).
3. Displays the full DataFrame: **254,553 rows × 21 columns**.

## Dataset
**File:** `industryAnalysis_2000_2022.csv` (not included in this repo — add separately or via `.gitignore` note if the source data is restricted).

**Key columns include:**
| Column | Description |
|---|---|
| `gvkey` | Firm identifier (Compustat global company key) |
| `datadate` | Fiscal period end date |
| `fyear` | Fiscal year |
| `tic` | Ticker symbol |
| `conm` | Company name |
| `curcd` | Currency code |
| `at` | Total assets |
| `cogs` | Cost of goods sold |
| `csho` | Common shares outstanding |
| `emp` | Employees |
| `ib` | Income before extraordinary items |
| `oibdp` | Operating income before depreciation |
| `sale` | Net sales/revenue |
| `costat` | Company status (Active/Inactive) |
| `prcc_c` | Calendar-year close price |
| `naics` | NAICS industry classification code |

## Requirements
- Python 3
- `pandas`
- `numpy`

## How to run
```bash
pip install pandas numpy
jupyter notebook AFM244_QUIZ2.ipynb
```
Ensure `industryAnalysis_2000_2022.csv` is in the same directory as the notebook.

## Notes
This notebook currently covers **data loading and inspection only** — no cleaning, transformation, or analysis has been added yet. Update this README if further analysis is added to the notebook.

## Author
Prachee — School of Accounting and Finance (AFM), University of Waterloo
