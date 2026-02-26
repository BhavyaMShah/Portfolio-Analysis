# 📊 Portfolio Analysis — Intrinsic Valuation Framework (Python)

## Overview

This project is a **portfolio-focused Discounted Cash Flow (DCF) valuation engine** built in Python to estimate the intrinsic value of multiple companies and evaluate their contribution within an investment portfolio.

The framework supports **bottom-up security analysis**, **capital allocation decisions**, and **intrinsic vs. market value comparison** at both the security and portfolio level.

---

## 🔍 What the framework does

- Calculates **Free Cash Flow to the Firm (FCFF)** for each portfolio constituent  
- Estimates **Cost of Equity using CAPM**  
- Computes **Weighted Average Cost of Capital (WACC)** with strict unit consistency  
- Forecasts company-level cash flows over a defined investment horizon  
- Calculates **terminal value using the Gordon Growth Model**  
- Derives **enterprise value, equity value, and intrinsic value per share**  
- Aggregates intrinsic values across holdings to analyze **portfolio-level intrinsic exposure**  
- Enables comparison between **intrinsic portfolio value and market portfolio value**

---

## 🧠 Portfolio-centric design philosophy

- Built for **multi-asset valuation**, not single-stock analysis  
- Emphasizes **capital structure awareness** across portfolio holdings  
- Designed to highlight **mispricing at both security and portfolio level**  
- Clean separation between:
  - Fundamental inputs  
  - Valuation mechanics  
  - Portfolio aggregation logic  
- **Unit-safe implementation** to ensure consistent and comparable portfolio outputs  

---

## 📁 Input structure

The model ingests a structured **Excel / CSV file** containing:

- Company-level operating and cash flow data  
- Risk and return assumptions (risk-free rate, expected market return, beta)  
- Capital structure inputs (debt and equity)  
- Growth and terminal assumptions  
- Shares outstanding and portfolio position sizes  

This allows the same valuation engine to be applied **consistently across entire portfolios**.

---

## ▶️ How to use

1. Download the provided Excel template  
2. Populate the file with your portfolio and company-level data  
3. Open the notebook / script and run the code  
4. Execute the function:

5. You will be prompted to **upload the Excel file**  
6. Once uploaded, the model will automatically:
    - Perform DCF valuation for each company  
    - Aggregate intrinsic values at the portfolio level  
    - Output intrinsic vs. market portfolio comparisons  

The final output provides both **security-level valuation results** and **portfolio-level insights**.

---

## 📊 Portfolio insights enabled

- Intrinsic value contribution of each holding  
- Aggregate intrinsic portfolio value  
- Comparison of **intrinsic allocation vs. market allocation**  
- Identification of **over- and under-weighted positions** based on fundamentals  
- Framework for **rebalancing and long-term capital allocation analysis**

---

## ⚠️ Scope & limitations

- Designed for **non-financial companies**  
- Assumes deterministic growth and discount rates  
- Intended as a **valuation and portfolio analysis tool**, not a trading or execution system  

---

## 🚀 Possible extensions

- Portfolio-level sensitivity and scenario analysis  
- Risk-adjusted intrinsic allocation metrics  
- Integration with factor models (CAPM, Fama-French)  
- Efficient frontier construction and rebalancing logic  
- Object-oriented refactor for scalable portfolio analysis  

---

## 📌 Disclaimer

This project is for **educational and analytical purposes only** and should not be considered investment advice.
