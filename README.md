<h1 align="center">
  Digital Marketing Campaign Conversion Prediction
</h1>
<div align="center">
  <h4>Aurthor: <a href="https://www.linkedin.com/in/deveena-vig-73b582232/">Deveena Vig</a></h4>
</div>

## Overview:
Marketers struggle to allocate budgets effectively due to uncertainty about customer behavior.
Misallocations lead to wasted resources and missed revenue opportunities. 
By predicting customer conversions, this project seeks to minimize these inefficiencies and guide data-driven decision-making for better campaign outcomes.
Additionally, we developed a Power BI dashboard to further analyze campaign conversion prediction results and provide interactive visualizations for stakeholders.

## Problem Statement:
The Objective of this project are as follows:
1. Develop a robust predictive model: Accurately predict whether a customer will convert based on demographic and engagement features.
2. Optimize marketing strategies: Improve campaign targeting, increase conversion rates, and maximize return on advertising spend (ROAS).

## Dataset Description:
- 8000 rows and 20 columns
- Attributes include Demographic Information, Marketing Specific Variables, Customer Engagement Variables, Historical Variables and Conversion ( Converted for 1 and 0 for not )

## Machine Learning Task:
This project employs supervised learning, specifically a classification task, to predict converted customers. Three algorithms were utilized: Decision Tree, Random Forest, Gradient Bossting and CatBoost. Each algorithm was evaluated with and without balancing techniques, including over-sampling.

## Methodology:
### Data Analysis:
- Exploratory Data Analysis (EDA) to understand data distribution and patterns
- Addressing class imbalance (more converted customers than not converted)
- Identifying factors influencing conversion

### Data Preprocessing:
- Handling missing values and outliers
- Transforming categorical variables (using encoding)
- Standard scaling numerical features

### Model Building and Evaluation:
- Training and evaluating models with and without data balancing
- Metrics used: confusion matrices, precision, recall, F1-score, accuracy and PR curve.

## Outcome:
CatBoost with and without over-sampling (SMOTE) chosen for high recall and balanced performance.

## Power BI Dashboard Development:
In addition to the machine learning model development, we also created a Power BI dashboard to further analyze the conversion prediction results and provide interactive visualizations for stakeholders.
<div align="center">
  <a href="https://github.com/Deveena0913/Digital-Marketing-Campaign-Conversion-Prediction-/blob/main/Digital%20Marketing%20Campaign%20Conversion%20Project%20Deveena%20Vig.pbix">
    <img src="">
  </a>
</div>
