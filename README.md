# Employee-Burn-and-Fatigue-Predictive-Analysis

<img width="853" height="1280" alt="Image" src="https://github.com/user-attachments/assets/33ade353-6f6d-43d7-b050-2dfac7789c4c" />

<img width="1254" height="1254" alt="Image" src="https://github.com/user-attachments/assets/c3eb1fc4-76b6-411e-80ed-ee359abdc2bc" />

<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/5da9731a-43d8-4474-801d-8c1399072da2" />

This work provides an exploratory analysis of employee workload, fatigue, and burn indicators across demographics, company type, work-from-home availability, and seniority. It highlights distributions, relationships, and potential risk areas, while handling missing values and outliers to ensure robust insights.
##📊 Regression Analysis: Designation vs Mental Fatigue

###📌 Overview

This project explores the relationship between Designation (independent variable) and Mental Fatigue Score (dependent variable) using a linear regression model.

The goal is to determine whether an increase in job designation is associated with higher levels of mental fatigue.

###🧮 Model Specification

The regression model is defined as:

[\text{Mental Fatigue Score} = 2.9113 + 1.0523 \times \text{Designation}]

Intercept (2.9113): Baseline mental fatigue when designation is zero
Slope (1.0523): Increase in mental fatigue for each unit rise in designation

###📈 Key Statistics
Metric	Value	Interpretation
Multiple R	0.486	Moderate positive correlation
R Square (R²)	0.236	23.6% of variation explained
Adjusted R²	0.236	Model remains stable
Standard Error	2.15	Moderate prediction error
Observations	22,749	Large dataset

###🧪 ANOVA Results
Source	df	SS	MS	F	Significance
Regression	1	32457.85	32457.85	7016.19	0.000
Residual	22747	105230.79	4.63	
Total	22748	137688.64	
	
👉 The model is statistically significant, meaning the relationship is not due to chance.

###📉 Coefficients Summary
Variable	Coefficient	P-value	Interpretation
Intercept	2.9113	0.000	Significant baseline fatigue
Designation	1.0523	0.000	Strong positive effect
👉 Both coefficients are highly significant.

###🔗 Correlation
Correlation coefficient ≈ 0.503
Indicates a moderate positive relationship between designation and mental fatigue.
🧠 Interpretation
There is a positive linear relationship between designation and mental fatigue.
As employees move to higher designations, their mental fatigue tends to increase.
However, the model explains only 23.6% of the variation, suggesting:
Other factors (e.g., workload, environment, stress) also influence fatigue.
⚠️ Limitations
The modelabove includes only one predictor (designation)
Moderate R² indicates missing explanatory variables which are explored below
Does not capture non-linear or complex relationships
🚀 Conclusion

This analysis confirms that designation significantly impacts mental fatigue, with higher roles associated with increased fatigue levels. However, the model has moderate predictive power.

## Additional variables to improve accuracy includes:

📊 Key Insights

###🧩 Resource Allocation
Resource allocation is highly concentrated: the top three allocation levels each hold ~14–18% of total share.
Smaller levels contribute minimally, with "Other" accounting for less than 1%, indicating strong clustering of resources.
Allocation increases steadily with designation (~1.21 → 9.19), showing that higher roles receive more resources.

###🔥 Burn Rate & Mental Fatigue
Burn rate rises significantly from ~15% (junior levels) to ~85.7% (highest designation).
Mental fatigue increases from ~2.64 to ~8.94 across designation levels.
Indicates a strong positive relationship between role seniority and stress levels.

###👥 Workforce Distribution
Mid-level designations (levels 1–3) have the largest employee population.
These levels therefore concentrate the highest overall burn and fatigue risk across the organization.

###📈 Trend Analysis
Average burn rate shows a steady upward trend with increasing designation.
Suggests progressively higher workload, responsibility, or pressure in senior roles.

###⚖️ Gender Insights
Males:
Burn ≈ 0.48
Fatigue ≈ 6.02
Females:
Burn ≈ 0.42
Fatigue ≈ 5.46

👉 The fatigue gap (~0.56) is larger than the burn gap, indicating deeper differences in experienced strain.

###🏢 Company Type Insights
Service companies employ roughly 2× more people than Product companies:
Service: ~14,833
Product: ~7,917
Both types show a similar distribution of WFH availability.

###🏠 Remote Work (WFH)
Remote work is widely available across both company types.
The "WFH Available" group is larger than the "Not Available" group.

###📅 Recent Hiring Trends
Past 12 months show stable hiring patterns:
Average Burn ≈ 0.45
Mental Fatigue ≈ 5.7 – 5.8
Monthly Headcount ≈ 1,800 – 1,970
Minimal variation suggests consistent workforce planning.

## I am available for future collaboration via email: dotunjoshua5@gmail.com 

## LinkedIn: Andrew Omotayo
