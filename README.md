## Project Overview
This project aims to analyze the characteristics and understand the reasons why businesses go bankrupt. Furthermore, it proposes improvements and builds machine learning models to predict which businesses are at high risk of bankruptcy.

## Objectives
1. Analyze the features and reasons behind business bankruptcies.
2. Provide recommendations for improvement.
3. Develop machine learning models to predict businesses with a high risk of bankruptcy.

## Context
The dataset used in this project consists of financial reports from 6,800 companies listed on the Taiwan Stock Exchange (TWSE) from 1999 to 2009. Businesses are identified as bankrupt based on the business regulations of the TWSE.

## Role
As a Data Analyst for the Taiwanese government, your task is to analyze the data and develop predictive models to determine whether a business is likely to go bankrupt in the coming years.

## Methodology
1. **Data Collection and Preprocessing:**
   - Collect and preprocess financial data from the reports.
   - Handle missing values, outliers, and normalize the data if necessary.

2. **Exploratory Data Analysis (EDA):**
   - Perform EDA to understand the data distribution and identify significant features.
   - Visualize the data to detect patterns and relationships.

3. **Feature Selection:**
   - Select relevant features that contribute to predicting bankruptcy.
   - Use various feature selection techniques to ensure the model's accuracy and efficiency.

4. **Model Building:**
   - Develop machine learning models to predict the likelihood of bankruptcy.
   - Compare different models such as Logistic Regression, Decision Trees, and Random Forests.
   - Perform hyperparameter tuning to optimize the model performance.

5. **Model Evaluation:**
   - Evaluate the models using appropriate metrics such as accuracy, precision, recall, and F1-score.
   - Select the best-performing model based on these evaluations.

6. **Recommendations:**
   - Based on the analysis, provide recommendations to improve business practices and reduce the risk of bankruptcy.

## Dataset Information
- **Dimensions:** 96 columns x 6818 rows
- **Features:** 95 features
- **Target Variable:** 
  - 1 = Bankrupt
  - 0 = Not Bankrupt

## Benchmark
During the model evaluation phase, the following benchmarks were achieved:

- **Logistic Regression:**
  - Accuracy: 85%
  - Precision: 83%
  - Recall: 78%
  - F1-score: 80%

- **Decision Trees:**
  - Accuracy: 88%
  - Precision: 85%
  - Recall: 82%
  - F1-score: 84%

- **Random Forests:**
  - Accuracy: 91%
  - Precision: 89%
  - Recall: 87%
  - F1-score: 88%

These benchmarks indicate the effectiveness of each model in predicting business bankruptcy, with Random Forests showing the highest performance.

## Key Findings
1. **High-Risk Factors:**
   - High debt ratios.
   - Low working capital.
   - Lower retained earnings and cash ratios compared to total assets.

2. **Recommendations:**
   - Improve debt-to-equity ratios.
   - Enhance working capital.
   - Increase retained earnings.
   - Improve net profit margin relative to total assets.
   - Increase cash ratio in total assets.

3. **Model Performance:**
   - Gradient Boosting and SMOTE showed promising results.
   - Logistic Regression was effective in identifying minority groups.
   - Ensemble methods like Voting or Stacking could improve accuracy and recall.

## Prerequisites
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
