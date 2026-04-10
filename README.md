# Weekly-Portfolio-Analysis 📈

A hybrid architecture system (Excel + Python) designed for the active management and quantitative analysis of an investment portfolio. 

This project automates the calculation of complex financial metrics for a short-term investment horizon. By separating the manual trade entry (Input Layer) from the data processing (Processing Layer), the system ensures scalability and reduces human error.

### 🚀 Key Features:
* **Automated Consolidation:** Updates current positions, portfolio weights (%), and cash balances based on a raw trade ledger (buys/sells).
* **Benchmarking:** Compares cumulative and weekly portfolio performance against the S&P 500.
* **Risk & Return Metrics:** Automated calculations using `pandas` and `numpy` to retrieve the Sharpe Ratio, Information Ratio, Portfolio Volatility, Tracking Error, and Maximum Drawdown.
* **Clean Dashboard:** Direct export of processed dataframes into an Excel template that acts strictly as a visualization layer.

***
