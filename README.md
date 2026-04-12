# 📊 Bank Valuation Model – JPMorgan (DCF vs DDM Analysis)

## 🔹 Overview

This project builds a structured equity valuation model for JPMorgan using Power BI, combining a Free Cash Flow to Firm (FCFF)-based Discounted Cash Flow (DCF) approach with a Dividend Discount Model (DDM).

The objective is to evaluate valuation consistency across methods and highlight the limitations of traditional DCF when applied to banking institutions.

---

## 🔹 Key Findings

- **DCF Valuation:** ₹1.38T  
- **DDM Valuation:** ₹187.97  
- **Market Price:** ₹1.50K  
- **Conclusion:** DCF output is structurally distorted; DDM provides a more reliable valuation anchor  
- **Primary Driver:** Cost of equity (13%) and dividend growth assumptions  

---

## 🔹 Why DCF Fails for Banks

Traditional DCF (FCFF) breaks down for banks due to structural differences:

- **Debt is operational, not financing**  
  Deposits act as a core input rather than a funding choice  

- **No clear reinvestment definition**  
  Lending growth and capital adequacy obscure reinvestment metrics  

- **WACC becomes less meaningful**  
  Separation of debt and equity loses relevance in banking  

- **Regulatory capital constraints**  
  Basel norms and capital requirements restrict deployable cash flows  

- **Cash flow volatility**  
  FCFF fluctuates with interest rate cycles, reducing reliability  

---

## 🔹 Alternative Approach: Dividend Discount Model (DDM)

Given the limitations of DCF, DDM is used as a more suitable valuation method.

**Rationale:**

- Banks distribute value primarily through dividends  
- Dividends are more stable and regulated  
- Aligns valuation with actual shareholder cash flows  

**Model Logic:**

- Based on expected future dividends  
- Cost of equity derived using CAPM  
- Growth estimated using historical dividend trends  

---

## 🔹 Key Assumptions

- **Cost of Equity:** 13% (CAPM-based)  
- **Dividend Growth Rate:** Based on historical trends  
- **Terminal Growth Rate:** Conservative, aligned with long-term macro growth  
- **Beta:** Industry benchmark / assumed  
- **Dividend Stability:** Derived from historical payout consistency  

---

## 🔹 Power BI Dashboard

The interactive dashboard enables dynamic exploration of valuation drivers:

- Visualizes **cash flow breakdown (operating, investing, financing)**  
- Displays **DCF valuation vs market price comparison**  
- Tracks **historical dividend trends**  
- Includes **DDM sensitivity analysis (growth vs cost of equity)**  

**User Controls:**

- Adjust growth rate (g)  
- Modify cost of equity (Ke)  
- Instantly observe valuation impact  

---

## 🔹 Limitations

- High sensitivity to **growth and cost of equity assumptions**  
- Dividend projections rely on historical trends which may not persist  
- Regulatory changes can impact payout capacity  
- DCF results are included for comparison but are not reliable for banks  

---

## 🔹 Final Takeaway

DCF may be the default valuation tool, but for banks it can produce misleading results. A dividend-based approach provides a cleaner and more realistic estimate of shareholder value.

---

~Sanvi Mahajan ✿
