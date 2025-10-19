# 2214 Asset Management Group Assignment - Summary

This project executes a comprehensive analysis of active and passive investment strategies, structured across three interconnected modules: mutual fund performance evaluation, constrained mean-variance portfolio optimization, and an in-depth study of a renowned investor's strategy (Buffett's Alpha).

---

##  Project Goals

| Module | Primary Goal | Data Utilized |
| :--- | :--- | :--- |
| **1. Performance Analysis (10 Funds)** | Evaluate the **alpha and value-added** (gross and net) of 10 active mutual funds against various benchmarks (CAPM, FF5, CPZ Index-Based), and characterize their factor exposures. | Mutual fund returns, fees, AUM, CPI, FF 5-Factor returns. |
| **2. Portfolio Choice (21 Assets)** | Construct and back-test **optimal portfolios** (Tangency and Minimum Variance) from a universe of 21 risky assets (10 active funds and 11 passive index funds) under practical investment constraints. | Returns for 10 active and 11 passive index funds, risk-free rate. |
| **3. Buffett's Alpha** | Determine the factor-adjusted performance (alpha) of **Berkshire Hathaway** and its public stock portfolio, and analyze the financial and factor characteristics of key acquisitions (Lubrizol, Heinz). | Berkshire returns, public stock portfolio returns, factor returns, Lubrizol/Heinz data. |

---

##  Key Findings (Anticipated)

The analysis is expected to provide insights into modern investment practices and the active versus passive debate:

* **Fund Performance:** Performance measures, particularly **Net Value Added** (which accounts for fees, inflation-adjusted AUM, and alpha ), will identify which fund managers generated the most absolute wealth for their investors.
* **Factor Exposures:** Fund factor betas (FF5) will characterize the investment styles (e.g., size, value) of the funds, which will be used to logically **match the funds to their qualitative strategy descriptions** provided in the Appendix.
* **Optimal Portfolios:** The efficient frontier constructed under constraints (e.g., max 10% active weight, min 50% passive weight ) will demonstrate the trade-off between risk and return, validating the benefits of combining active management with low-cost passive vehicles.
* **Buffett's Alpha:** The results will compare the performance, volatility, and factor loadings of Berkshire Hathaway versus its public stock holdings, suggesting that total performance is derived from sources beyond public stock picking. Key acquisitions are expected to show value-oriented financial characteristics (e.g., high $\mathbf{B/M}$ or $\mathbf{E/P}$) consistent with fundamental analysis.
