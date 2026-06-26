# 📊 Financial Management — Assignment 3
## Beta Analysis, CAPM & Security Market Line (SML)
### KSE-100 Index | Pakistan Stock Exchange

This assignment applies the **Capital Asset Pricing Model (CAPM)** 
framework to evaluate the systematic risk and expected return of 
4 Pakistani companies listed on the **Pakistan Stock Exchange (PSX)**, 
benchmarked against the **KSE-100 Index**.



## Companies Analyzed
| # | Company | Ticker | Sector | Beta (β) |
|---|---------|--------|--------|----------|
| 1 | Lucky Core Industries | LUCK | Cement / Industrials | 0.674 |
| 2 | Allied Bank Limited | ABL | Banking / Financial | 0.565 |
| 3 | National Foods Limited | NATF | Consumer Staples | 0.686 |
| 4 | Nestle Pakistan | NESTLE | FMCG | 0.006 |

## 🔍 Analysis Performed
- ✅ **Beta Estimation** via regression of company returns vs KSE-100
- ✅ **Scatter Plot Visualization** of return relationships
- ✅ **Portfolio Beta Calculation** (two weighting schemes)
- ✅ **CAPM Required Return** estimation for each asset
- ✅ **Security Market Line (SML)** construction & valuation

## 📊 Key Results

### Beta Values (All Defensive — β < 1)
- Lucky Core Industries → β = 0.674
- Allied Bank Limited → β = 0.565
- National Foods Limited → β = 0.686
- Nestle Pakistan → β = 0.006 *(near-zero market sensitivity)*

### Portfolio Beta
| Portfolio | Beta |
|-----------|------|
| Original (30/30/20/10 weights) | 0.5095 |
| New (25/15/40/20 weights) | 0.9213 |

### CAPM Parameters
- Risk-Free Rate (Rf): **11.89%**
- Market Return (Rm): **30.96%**
- Market Risk Premium: **19.07%**

### SML Valuation
| Company | Required Return | Actual Return | Status |
|---------|----------------|---------------|--------|
| Lucky Core | 24.75% | 14.47% | ❌ Undervalued |
| Allied Bank | 22.66% | 12.80% | ❌ Undervalued |
| National Foods | 24.97% | 28.99% | ✅ Overvalued |
| Nestle Pakistan | 12.00% | 3.43% | ❌ Undervalued |

## 🛠️ Tools Used
- Microsoft Excel (Regression, Charts, CAPM formulas)
- KSE-100 Historical Data
- Pakistan T-Bill Rate as Risk-Free Rate
