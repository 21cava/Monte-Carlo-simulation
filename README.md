# 🇮🇹 Monte Carlo Portfolio Optimization - Borsa Italiana Edition

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Finance](https://img.shields.io/badge/Finance-Quantitative-green)
![Status](https://img.shields.io/badge/Status-Active-success)

## 📋 Project Overview
This project applies **Modern Portfolio Theory** specifically to the **Italian Stock Market (Piazza Affari)**, using a localized risk-free rate based on **Italian Government Bonds (BTP)**.

Using a **Monte Carlo Simulation** with 10,000 iterations, the algorithm identifies the optimal asset allocation to maximize the **Sharpe Ratio**.

### 🎯 Key Features
* **Italian Market Focus:** Optimized for tickers from Borsa Italiana
* **Localized Risk-Free Rate:** The Sharpe Ratio calculation uses a custom risk-free rate based on **Italian Government Bonds (BTP)** yields, rather than the standard US Treasury rate, for a more specific valuation.
* **Quantitative Analysis:**
    * Log-Returns calculation for additive properties.
    * Annualized Covariance Matrix computation.
* **Markowitz portfolio theory**: The output portfolio is the result of the Markowitz theory to maximize the expected return for a given level of risk.

## 🛠️ Technologies
* Language: **Python**
*  Library: **NumPy:**, **Pandas:**, **Matplotlib:** , **yfinance:**

## 📈 Example Assets Analyzed
The project currently analyzes 5 of the most important Italian assets:
* **Ferrari (RACE.MI):** Luxury / Automotive
* **Enel (ENEL.MI):** Utilities / Energy
* **Intesa Sanpaolo (ISP.MI):** Banking
* **Eni (ENI.MI):** Energy / Oil & Gas
* **Unicredit (UCG.MI):** Banking

## ⚠️ Disclaimer
This project is for educational and research purposes only. It does not constitute financial advice. Past performance is not indicative of future results.

---
*Created by L.*
