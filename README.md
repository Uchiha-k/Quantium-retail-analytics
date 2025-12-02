#  Quantium Retail Analytics – Task 2: Trial Layout Assessment

This repository contains my full workflow for **Quantium’s Task 2**, where I assessed the impact of new chip layouts in trial stores against matched control stores. The project combines statistical uplift testing, confidence interval visualizations, and clear rollout recommendations.

---

##  Project Summary

- **Objective**  
  Test whether new product layouts in trial stores (77, 86, 88) led to significant uplift in sales and customer counts compared to matched control stores.

- **Methodology**  
  - Control store selection using correlation and magnitude distance  
  - Trial period defined as **Feb–Apr 2019**  
  - Metrics analyzed: **Total Sales** and **Number of Customers**  
  - Uplift testing with percentage differences and t‑tests  
  - Confidence band visualizations to highlight significance  

- **Results**  
  - **Store 77** → Significant uplift in March & April → ✅ Roll out  
  - **Store 86** → Uplift in customers but not sales → ⚠️ Retest  
  - **Store 88** → Consistent uplift across trial months → ✅ Roll out  

---

##  Deliverables

- **Jupyter Notebook**: Full pipeline with analysis and visualizations  
- **Visuals**: Trial vs. control charts with 95% confidence bands (see `/outputs`)  
- **Summary Table**: Recommendations per store  
- **Executive Summary**: Clear rollout guidance for stakeholders  

---

##  Visual Examples

Each chart compares trial vs. control sales, highlights the trial period, and overlays confidence intervals:

- Store 77 → Significant uplift in March & April  
- Store 86 → Customer uplift but no consistent sales uplift  
- Store 88 → Strong uplift across trial months  

---

##  Tech Stack

- Python (pandas, numpy, seaborn, matplotlib, scipy)  
- Jupyter Notebook  
- Git + GitHub for version control and publishing  

---

##  Executive Summary

> The trial layout delivered strong results in stores 77 and 88, with statistically significant uplift in sales during the trial period. Store 86 showed increased customer traffic but no consistent sales uplift.  
> **Recommendation:** Roll out the new layout to stores 77 and 88, and conduct a targeted retest for store 86.

---

## 📁 Repo Structure
