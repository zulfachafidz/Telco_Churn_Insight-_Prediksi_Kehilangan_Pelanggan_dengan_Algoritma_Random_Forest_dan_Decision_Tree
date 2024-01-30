# Telco Churn Insight: Memprediksi Kehilangan Pelanggan dengan Algoritma Random Forest dan Decision Tree

## Description
The main problem in the business world is customer churn, or losing customers, especially in the telecommunications industry, which experiences very tight competition. To overcome this problem, an analysis was carried out to help the company understand how many customers have the potential to switch providers.

## analysis objectives
Developing a classification model using decision trees and Random Forest to predict customer loss in telecommunications companies. The hope is that the resulting model can help companies understand how many customers are leaving the business and the reasons behind their decision to leave.

## Data Collection
The dataset was obtained directly from GitHub via the following source: [Telco-Customer-Churn Dataset](https://github.com/arubhasy/dataset/blob/main/Telco-Customer-Churn.csv)

## Bahasa 
**Programming Language**: Python

**Libraries used**: numpy, pandas, matplotlib, plotly express, seaborn, scikit-learn

## Data Analysis
### 1. Data Understanding
Understanding data involves analyzing data types, the volume of each category, and comparing customer churn and no churn.

### 2. Data Preparation
- **Data Cleaning**: Uses a method of removing null values ​​because only a small amount of data has null values.
- **Data Transformation**: Changes the data type and deletes unused columns.

### 3. Splitting data
The separation between test data and train data uses a ratio of 80:20.

### 4. Modelling
Application of classification methods using the Decision Tree and Random Forest algorithms.

### 5. Modeling Results and Model Evaluation
#### Decision Tree
The accuracy rate is 72% with positive evaluations being higher than negative. The evaluation showed that the TN (True Negative) was 852 and the TP (True Positive) was 166.

#### Random Forest
The accuracy rate is 81% with positive evaluations being higher than negative. Evaluation shows TN of 959 and TP of 174.

Based on the comparison, the model using the Random Forest algorithm is better with the following evaluation results:
- **Accuracy**: 81%
- **Precision**: 85%
- **Recall**: 91%
- **F1-Score**: 88%

### 6. Identify variables that influence customer churn
Feature Importance using Random Forest shows that the most influential variable is Total Charges.

Conclusion: customers with high Total Charges have the potential to churn more quickly.
