# Bank-Valuation-Model-JPMorgan-DCF-vs-DDM-Analysis

## Overview

This project builds a structured equity valuation model for JPMorgan using Power BI, combining a Free Cash Flow to Firm (FCFF) based Discounted Cash Flow approach with a Dividend Discount Model (DDM).

The objective was to evaluate valuation consistency across methods and highlight the limitations of traditional DCF when applied to banking institutions.

---

## Model Structure

The model integrates:

- Income Statement  
- Balance Sheet  
- Cash Flow Statement  

Raw financial data was transformed and standardized using Power Query, enabling consistent calculation of valuation metrics across time.

A mapping table was created to align raw line items with standardized financial categories.

---

## Valuation Approaches

### 1. FCFF-based DCF

- FCFF derived from operating metrics  
- Discounted using WACC  
- Incorporates assumptions for growth and capital structure  

### 2. Dividend Discount Model (DDM)

- Based on latest annual dividend  
- Applies constant growth assumption  
- Produces intrinsic value per share  

---

## Key Features

- Data cleaning and normalization using Power Query  
- Standardization of financial line items via mapping table  
- Calculation of Net Income, EBIT proxy, Depreciation, CapEx, and Working Capital  
- WACC computation using CAPM inputs  
- FCFF estimation and DCF valuation logic  
- Dividend aggregation and DDM valuation  
- Calendar table integration for time-based analysis  

---

## Assumptions

- Risk Free Rate: 7%  
- Beta: 1.1  
- Market Return: 12%  
- WACC: 12.5%  
- Growth Rate: 4%  

---

## Key Findings

### 1. DCF limitations for banks

Traditional DCF assumptions do not hold well for banks. Debt is treated as an operating component rather than purely financing, which distorts capital structure assumptions and affects FCFF reliability.

### 2. Working Capital is not meaningful

Conventional working capital definitions break down in banking due to the nature of deposits and lending activities. This reduces the effectiveness of FCFF-based modeling.

### 3. DDM provides a more stable valuation signal

Dividend-based valuation aligns better with how banks generate and distribute value. The DDM approach produced a more stable and interpretable intrinsic value compared to DCF.

### 4. Sensitivity to assumptions

Valuation outcomes are highly sensitive to WACC and growth rate inputs, reinforcing the importance of transparent and realistic assumptions.

---

## Results

- WACC: **12.5%**  
- DDM Valuation: **~$5.5 per share**  

DCF results showed higher variability due to structural limitations in modeling banking cash flows.

---

## Conclusion

This project demonstrates that while DCF remains a widely used valuation method, it is not always appropriate for financial institutions. Alternative approaches such as DDM can provide more reliable insights when aligned with the business model.

The combination of both methods offers a more balanced perspective on valuation.

---

~Sanvi Mahajan ✿
