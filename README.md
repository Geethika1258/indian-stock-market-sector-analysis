# indian-stock-market-sector-analysis
NSE sector performance analysis using real stock data — identifying top performing sectors, volatility patterns and investment insights across 10 sectors and 48 companies (2023-2024). Built with Python and Power BI.

## Business Problem
Which NSE sectors delivered the best returns and lowest risk for investors in 2023-2024? And how did sector performance shifgt between the two years?

## Dataset
- Real stock data fetched using yfinance API
- 48 companies across 10 NSE sectors
- 23,501 rows of daily price data
- Data range: January 2023 - December 2024

## Sectors Covered
BANKING | it | pharma | Auto | FMCG | 
Energy | Metal | Realty | Infra | Media

## Approach 
1. Live data fetching using yfinance API
2. Data cleaning and return calculation
3. Sector performance and volatility analysis
4. Annual return comparision 2023 vs 2024
5. Interactive Power BI dashboard with slicers

## Key Findings
1. ** Realty ** is the best performing sector -
   avg daily return of 0.223%
2. ** Media ** is the worst - negative returns (-0.026%)
   with highest volatility (2.614)
3. ** FMCG ** is the safest - lowest volatility (1.189) ,
   ideal for risk-averse investors
4. ** INFRA and Energy ** follow realty as consistent
   outperformers

## Sector Performance Summary
 | Sector | Avg Daily Return | Volatility | Risk Level | 
 |--------|------------------|------------|------------|
 | Realty | 0.223% | 2.235 | Medium-High |
 | Infra | 0.130% | 2.588 | High | 
 | Energy | 0.126% | 1.707 | Medium | 
 | Auto | 0.120% | 1.476 | Medium |
 | Pharma | 0.117% | 1.386 | Medium |
 | IT | 0.105% | 1.434 | Medium | 
 | Metal | 0.093% | 1.778 | Medium |
 | Banking | 0.044% | 1.345 | Low-Medium |
 | FMCG | 0.030% | 1.189 | Low |
 | Media | -0,026 % | 2.614 | Very High |

## Business Recommendation 
 Investors seeking growth should overweight Realty , Infra and Energy. Risk-averse investors should favour FMCG for stability. Media sector should be avoided - negative returns with highest volatility make it poor risk-adjusted investment.

## Dashboard
https://github.com/Geethika1258/indian-stock-market-sector-analysis/blob/main/dashboard_screenshot.png.png


## Tools 
Python | yfinance | Pandas | Numpy | Matplotlib | 
Seaborn | Power BI 

## Files 
- `Indian_Stock_Market_Sector_Analysis.ipynb` — 
  full analysis notebook
- `nse_powerbi.csv` — cleaned dataset for dashboard
- `sector_summary.csv` — sector level summary statistics
- `annual_returns.csv` — annual return by sector and year
- `NSE_Sector_Performance_Dashboard.pdf` — Power BI dashboard
- `sector_returns.png` — avg daily return chart
- `sector_volatility.png` — volatility comparison chart
- `annual_returns.png` — 2023 vs 2024 comparison
- `monthly_trend.png` — monthly return trend

## Related Projects
- [Motor Insurance Claims Analysis]
  https://github.com/Geethika1258/motor-insurance-claims-analysis/tree/main
- [Insurance Pricing A/B Test]
  https://github.com/Geethika1258/insurance-pricing-ab-test-analysis/tree/main
   
