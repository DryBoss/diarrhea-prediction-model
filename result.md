# Statistical Analysis

## Correlation Analysis

### **Pearson Correlation (Linear Relationship)**
| Factor               | Correlation | p-value  | Interpretation |
|----------------------|-------------|----------|----------------|
| **Minimum Temperature** | 0.268       | 0.000    | Weak positive correlation, statistically significant. |
| **Maximum Temperature** | 0.439       | 0.000    | Moderate positive correlation, statistically significant. |
| **Humidity**           | -0.231      | 0.000    | Weak negative correlation, statistically significant. |
| **Precipitation**      | -0.044      | 0.248    | No significant correlation (**p > 0.05** means no statistical significance). |

### **Spearman Correlation (Non-Linear Relationship)**
| Factor               | Correlation | p-value  | Interpretation |
|----------------------|-------------|----------|----------------|
| **Minimum Temperature** | 0.217       | 0.000    | Weak positive correlation, statistically significant. |
| **Maximum Temperature** | 0.412       | 0.000    | Moderate positive correlation, statistically significant. |
| **Humidity**           | -0.155      | 0.000    | Weak negative correlation, statistically significant. |
| **Precipitation**      | 0.064       | 0.090    | Very weak positive correlation, but **not statistically significant (p > 0.05)**. |

## ANOVA Results

| Factor                  | Sum of Squares | df  | F-Value   | p-value  | Interpretation |
|-------------------------|----------------|-----|-----------|----------|----------------|
| **Minimum Temperature** | 978.33         | 1.0 | 2.5926    | 0.108    | Not significant |
| **Maximum Temperature** | 9643.79        | 1.0 | 25.5563   | 0.000    | Significant effect |
| **Humidity**            | 224.28         | 1.0 | 0.5944    | 0.441    | Not significant |
| **Precipitation**       | 49.64          | 1.0 | 0.1316    | 0.717    | Not significant |

## Final Interpretation
- **Maximum Temperature significantly affects diarrhea cases (p < 0.05 → 0.000).**
  - Confirms correlation results, indicating **higher max temperatures link to increased diarrhea cases**.
  - The **F-value (25.56)** is the highest, meaning it has the strongest effect among all variables.
- **Minimum Temperature does NOT significantly affect diarrhea cases (p = 0.108).**
  - Despite weak correlation, regression analysis suggests it **is not a reliable predictor**.
- **Humidity does NOT significantly affect diarrhea cases (p = 0.441).**
  - Weak negative correlation but **not statistically significant**.
- **Precipitation does NOT significantly affect diarrhea cases (p = 0.717).**
  - No noticeable impact on diarrhea cases.

## Conclusion
- **Maximum Temperature is the only significant factor affecting diarrhea outbreaks.**
- **Minimum Temperature, Humidity, and Precipitation do NOT have a statistically significant effect.**

---

### Notes
- **Pearson correlation** measures **linear** relationships.
- **Spearman correlation** measures **monotonic** relationships (linear or non-linear).
- **ANOVA tests** determine whether **each variable has a significant effect** on diarrhea cases.

