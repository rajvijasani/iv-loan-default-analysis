# IV Loan Default Analysis

Causal inference analysis estimating the effect of debt-to-income ratio on loan default risk using instrumental variables (2SLS).

## Motivation
OLS estimates are likely biased due to endogeneity — borrower risk affects both DTI and default probability simultaneously. 2SLS with a valid instrument isolates the causal effect and shows the OLS estimate is substantially biased upward.

## Methods
- Two-stage least squares (2SLS)
- Multiple imputation (MICE) for missing data
- OLS and 2SLS estimates compared directly

## Language
R (analysis rendered as HTML via R Markdown)

## Files
- `IV_Analysis_MICE_Clean.html` — full analysis with code and output (open in browser)
- `Final Report.pdf` — written report with results and interpretation
- `Loan_Default.csv` — dataset
