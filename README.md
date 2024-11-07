# virtual-internship-BCGX-forage
![image](https://github.com/user-attachments/assets/34bee57e-4c3a-403d-88a8-20e1c5c94298)
# Customer Churn Analysis - BCGX Forage Virtual Internship

## Project Overview
PowerCo, a major gas and electricity utility provider, is facing increased customer churn in the SME (Small & Medium Enterprise) segment due to energy market liberalization in Europe. The primary goal of this project is to analyze and predict customer churn, specifically by evaluating if price sensitivity is a significant driver, and to support decision-making on offering targeted discounts to retain high-risk customers.

The project consists of several stages, including hypothesis formulation, exploratory data analysis (EDA), feature engineering, predictive modeling, and summarizing findings. A Random Forest classifier is trained to predict churn probability, supporting PowerCo in their strategy to offer a 20% discount to price-sensitive customers.

## Table of Contents
- [Task 1: Hypothesis Formulation](#task-1-hypothesis-formulation)
- [Task 2: Exploratory Data Analysis](#task-2-exploratory-data-analysis)
- [Task 3: Feature Engineering & Modeling](#task-3-feature-engineering--modeling)
- [Task 4: Findings & Recommendations](#task-4-findings--recommendations)
- [Technologies Used](#technologies-used)

---

## Task 1: Hypothesis Formulation
**Objective**: Diagnose the reasons behind SME customer churn, particularly focusing on price sensitivity as a primary driver.

### Approach:
- Define the problem as a data science challenge.
- Formulate the hypothesis: *"Churn is driven by customers' price sensitivity."*
- Outline steps to test this hypothesis:
  1. Gather data from the client on customer behavior, pricing, and churn indicators.
  2. Build a predictive model to identify customers at risk of churning.
  3. Assess customer churn likelihood under existing prices and evaluate potential impacts of offering a 20% discount.

### Required Data:
- **Client Data**: Customer information and demographic details.
- **Price Data**: Historical and current pricing information.
- **Churn Indicator**: Churn status data to serve as labels in the model.

---

## Task 2: Exploratory Data Analysis
**Objective**: Understand the dataset holistically and assess the correlation between price sensitivity and churn.

### Sub-Tasks:
1. **Exploratory Data Analysis**: Review data types, statistics, and distribution of variables.
2. **Hypothesis Testing**: Define and calculate "price sensitivity" and explore its correlation with churn rates.
3. **Key Findings Summary**: Prepare insights and suggest potential data augmentations.

### Suggestions for Data Augmentation:
- **External Data Sources**: Weather patterns, economic indicators, and competitor pricing data.
- **Client Data Enhancements**: Additional customer interaction data and service usage trends.

---

## Task 3: Feature Engineering & Modeling
**Objective**: Engineer relevant features, build a predictive churn model, and evaluate its performance.

### Sub-Tasks:
1. **Feature Engineering**: Enhance the dataset by creating new features, particularly:
   - Price sensitivity metrics, such as the difference between off-peak prices in December and January.
   - Additional customer behavior metrics that could indicate churn likelihood.
2. **Model Training**: Train a Random Forest classifier on the dataset to predict customer churn.
3. **Model Evaluation**: Assess model performance using metrics like accuracy, precision, recall, and F1 score.

### Random Forest Model Considerations:
- **Advantages**: Handles large datasets, reduces overfitting, interpretable feature importance.
- **Disadvantages**: Can be computationally intensive and less interpretable compared to simpler models.

**Bonus Insight**: Evaluate the potential financial impact of offering a 20% discount to customers with high churn probabilities, estimating potential cost savings.

---

## Task 4: Findings & Recommendations
**Objective**: Summarize findings for client stakeholders, focusing on actionable insights and financial impacts.

### Executive Summary:
- **Key Metric**: The churn model’s accuracy and the financial impact of targeted discounts.
- **Impact**: The model helps identify price-sensitive customers, enabling PowerCo to proactively retain high-risk customers and reduce churn.
- **Recommendation**: Consider implementing a targeted 20% discount for high-risk customers to maximize retention and optimize financial outcomes.

**Insights**: Avoiding churn through targeted discounts could save PowerCo significant revenue, especially in the SME segment.

---

## Technologies Used
- **Python**: Data analysis and modeling
- **Pandas**: Data manipulation
- **Scikit-learn**: Machine learning modeling
- **Matplotlib / Seaborn**: Data visualization

---

## Conclusion
This project provides a structured approach to diagnosing and mitigating customer churn within PowerCo's SME segment. Through predictive modeling and price sensitivity analysis, the insights generated enable PowerCo to apply targeted discounts strategically, supporting business sustainability in a competitive market.

