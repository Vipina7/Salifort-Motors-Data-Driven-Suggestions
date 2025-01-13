# Salifort Motors Employee Retention Project

## Overview

This project focuses on predicting employee turnover for Salifort Motors and identifying key factors that influence employee retention. Using machine learning models and feature engineering, this analysis provides actionable insights to help the Human Resources (HR) department improve employee satisfaction and reduce attrition.

---

## Problem Statement

Salifort Motors seeks to address the following question:

**What factors are likely to make an employee leave the company?**

This project explores employee-related data to build predictive models that assist HR in making data-driven decisions aimed at enhancing retention.

---

## Approach

- **Data Exploration**: Analyzed the dataset to understand key features and patterns.
- **Model Selection**: Implemented and compared logistic regression and tree-based models (e.g., Decision Tree, Random Forest).
- **Feature Engineering**: Created a new binary feature `overworked` to capture excessive work hours and evaluated the impact of existing features.
- **Model Evaluation**: Random Forest outperformed Decision Tree, providing better predictions and insights into feature importance.

---

## Key Findings

1. **Important Features**:
   - `last_evaluation`, `number_project`, `tenure`, and `overworked` were the most significant variables in predicting employee turnover.
   - Features like `salary_low` and `work_accident` also contributed to the model's accuracy.

2. **Insights**:
   - Employees working excessively long hours or handling too many projects are more likely to leave.
   - Employees with four years of tenure showed higher dissatisfaction rates.

3. **Model Performance**:
   - The Random Forest model slightly outperformed the Decision Tree model in predictive accuracy.

---

## Recommendations

Based on the findings, the following actions are recommended:

- Limit the number of projects assigned to employees to reduce workload stress.
- Investigate dissatisfaction among employees with four years of tenure and consider targeted retention strategies.
- Provide rewards or better compensation for overtime work and make workload expectations explicit.
- Address work culture issues by organizing team discussions and implementing changes based on feedback.
- Implement a proportionate evaluation system to recognize efforts equitably, especially for employees working extended hours.

---

## Ethical Considerations

- Ensured no bias in model predictions by reviewing features that could unfairly influence decisions (e.g., salary level, work accidents).
- Data privacy and confidentiality were maintained throughout the project.

---

## Resources

- Tools: Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Techniques: Logistic Regression, Random Forest, Feature Engineering
- References: Troubleshooting resources and documentation are cited within the notebook.

---

## Next Steps

- Explore other advanced machine learning models like Gradient Boosting or Neural Networks for further improvement.
- Collect additional data on employee satisfaction to enhance feature engineering.
