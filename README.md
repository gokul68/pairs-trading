# Pairs Trading with Cointegration and Regression

This project implements a statistical arbitrage framework for equity pairs trading, 
using cointegration tests for pair selection and linear regression for spread 
deviation modeling. The strategy was backtested on US equities from multiple sectors 
to evaluate robustness across in-sample and out-of-sample periods.

---

## Methods
- **Pair Selection:** Conducted Engle–Granger and Johansen cointegration tests to identify statistically robust pairs.  
- **Spread Modeling:** Applied linear regression to estimate spread deviations and generate long/short trading signals.  
- **Backtesting:** Evaluated performance using both in-sample (IS) and out-of-sample (OOS) data, focusing on Sharpe ratio and stability.  

---

## Key Findings
- Most sector pairs exhibited **Sharpe ratio decay** when tested out-of-sample.  
- **Industrial sector pairs (AME–DOV, AME–IEX)** maintained strong performance with **OOS Sharpe > 1.0**, 
  suggesting higher robustness under changing market conditions.  

---

