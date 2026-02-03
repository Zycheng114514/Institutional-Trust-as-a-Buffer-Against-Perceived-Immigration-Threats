# Institutional Trust as a Buffer Against Perceived Immigration Threats 

This repository contains materials for investigating the relationship between institutional trust and public attitudes toward immigration. Focusing on **Mainland China, Hong Kong, Taiwan, and Singapore**, this project explores how confidence in state institutions moderates the perception of immigration as a national benefit.

The final analysis and findings are documented in the Report in Document folder.
 
**Collaborators:** Zhiyang (Chris) Cheng, Jingwen (Wendy) Xiao

---

## 📌 Project Overview
As global migration shapes economic and community welfare, public sentiment becomes a critical driver of policy. This study utilizes individual-level data from the **World Values Survey (Wave 7, 2017–2022)** to analyze how trust in government shapes these views.

### Key Findings
* **Trust as a Positive Predictor:** Higher levels of institutional trust are consistently associated with more favorable evaluations of immigration’s impact on a country.
* **Regional Heterogeneity:** The "trust effect" is significantly stronger in high-immigration hubs like **Hong Kong** and **Singapore** compared to **Taiwan** and **Mainland China**.
* **Risk Mitigation:** The findings suggest that when citizens view state institutions as competent, they are more inclined to believe the government can manage migration risks effectively.

---

## 📊 Methodology
* **Data Source:** Individual-level responses from the **World Values Survey (WVS) Wave 7**.
* **Analytical Approach:** A three-stage Ordinary Least Squares (OLS) regression modeling approach:
    1. **Pooled Additive Model:** Establishes a baseline for the full sample while controlling for regional shifts.
    2. **Region-Specific Regressions:** Analyzes predictors within the unique socio-political context of each individual society.
    3. **Full Interaction Model:** Tests the marginal effect of trust across different regions using interaction terms.
* **Key Variables:**
    * **Dependent Variable:** Perceived overall impact of immigrants on national development (1–5 scale).
    * **Primary Explanatory Variable:** A composite **Institutional Trust Index** (confidence in police, courts, government, and civil service).
    * **Controls:** Education, Income, and Age.
* **Data Processing:**
* The sample is restricted to the four selected East Asian settings.
* Independent variables (Institutional Trust) are **mean-centered** to ensure the interpretability of interaction terms and coefficients.
* Cases with missing data on key analytical variables were dropped to ensure model consistency.

---

## 🔍 Other things to notice
1. An earlier version of this analysis, originally submitted for the course, is also included in this repository under `documents` folder. This version contains more complex analyses that are currently being refined and polished. The latest version contains a analysis that is more direct and intuitive.
