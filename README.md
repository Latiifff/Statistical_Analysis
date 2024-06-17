# Statistical Analysis with Spearman Correlation, Chi-Square Test, and Linear Regression 
This repository contains statistical analyses conducted on various datasets related to medical and health factors. The analyses include Spearman correlation, Chi-square test, and Linear Regression to explore relationships and predictive models related to heart attacks and other medical conditions.

## 📈 Correlation Analysis 
**Dataset Description:**
The dataset used for correlation analysis contains characteristics related to heart attacks or factors contributing to heart attacks.

**Results:**
Based on Spearman correlation analysis, the following relationships were observed:
- **Strong Positive Correlation:** Pressurelow and Pressurehight. Higher Pressurelow correlates strongly with higher Pressurehight.
- **Strong Positive Correlation:** Troppin and Class. Higher Troppin values correlate strongly with higher Class values.
- **Weak Positive Correlation:** Age with Pressurehight and Tropponin. Weak negative correlation between Age and Kcm, indicating older age correlates with higher Pressurehight and Tropponin levels, and lower Kcm.
- **Weak Positive Correlation:** Gender with Pressurehight and Tropponin.
- **Weak Positive Correlation:** Impulse with Pressurelow.
- **Weak Positive Correlation:** Kcm with Glucose. Weak negative correlation between Kcm and Troppin.

## 📊 Chi-Square Test Analysis 
**Dataset Description:**
The dataset includes symptoms and patient profiles across various diseases.

**Result Interpretations:**
1. **Fever, Cough, Fatigue:** Acceptance of H0 (p-value > 0.05) indicates no significant relationship with Disease.
2. **Difficulty Breathing:** Rejection of H0 (p-value < 0.05) indicates a significant relationship with Disease.
3. **Cough, Difficulty Breathing:** Acceptance of H0 (p-value > 0.05) suggests no significant relationship with Diagnosis (Outcome Variable).
4. **Fever, Fatigue:** Rejection of H0 (p-value < 0.05) indicates a significant relationship with Diagnosis.
5. **Age, Gender:** Acceptance of H0 (p-value > 0.05) indicates no significant relationship with Disease.
6. **Blood Pressure, Cholesterol Level:** Acceptance of H0 (p-value > 0.05) indicates no significant relationship with Disease. Rejection of H0 (p-value < 0.05) indicates a significant relationship with Diagnosis.

## 🚀 Linear Regression
**Dataset Description:**
The dataset consists of features aimed at predicting patients at high risk of heart disease.

**Results:**
The linear regression model demonstrates statistical significance (F-statistic = 17.65, p-value < 0.05) and explains a moderate portion of variance in Heart Disease (R-squared = 53.2%). Independent variables collectively contribute to predicting Heart Disease.

## 🎯 Conclusion 
This repository provides insights into statistical analyses using Spearman correlation, Chi-square test, and Linear Regression methods on medical datasets. These analyses enhance understanding of relationships between medical factors and conditions, facilitating informed decision-making in healthcare contexts.
