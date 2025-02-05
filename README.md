# Uber Data Analysis

## Dataset
The dataset used for this analysis is available on Kaggle:
- [Uber Data Analysis Dataset](https://www.kaggle.com/datasets/bhanupratapbiswas/uber-data-analysis)

## Collab 
- [Uber Data Analysis Project](https://colab.research.google.com/drive/1cruOCN5LX82xA_scMQaTQznsuUEf3Nxq?usp=sharing)

## Introduction
Uber is a leading ride-hailing service that connects passengers with drivers through a mobile application. This project analyzes Uber trip data to gain insights into trip patterns, mileage distribution, trip purposes, and trends over time. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling.

## Data Cleaning
Before performing any analysis, the dataset was cleaned to ensure accuracy. The following steps were undertaken:
- **Handling Missing Values:** Columns such as 'END DATE', 'CATEGORY', 'START', and 'STOP' with missing values were either dropped or filled appropriately.
- **Data Type Conversion:** Date columns were formatted correctly for proper analysis.
- **Checking Unique Values:** The 'CATEGORY' and 'PURPOSE' columns were examined to ensure consistency in data entries.
- **Handling Outliers:** Unusual values in numeric columns were identified and treated accordingly.

## Exploratory Data Analysis (EDA)
The dataset was explored using various visualizations and statistical techniques:
- **Histogram of Mileage:** A histogram was used to analyze the distribution of mileage, identifying common travel distances.
- **Box Plots:** Box plots were created to compare the distribution of mileage across different categories and purposes.
- **Scatter Plot of Mileage vs. Time:** This visualization highlighted patterns in trip distances over time.
- **Bar Chart of Trip Categories:** A bar chart displayed the distribution of business vs. personal trips, helping understand the nature of rides.

## Feature Engineering
New features were derived from existing data to improve the analysis:
- **Extracting Time Features:** The 'START DATE' column was used to extract hour, day, and month for time-based trend analysis.
- **Categorical Encoding:** The 'PURPOSE' and 'CATEGORY' columns were encoded for modeling purposes.

## Modeling and Predictive Analysis
A machine learning model was applied to predict trip categories based on available features. The following steps were undertaken:
- **Data Preparation:** Splitting the data into training and testing sets.
- **Model Selection:** Evaluating classification models such as Decision Trees and Logistic Regression.
- **Performance Metrics:** Accuracy, precision, and recall were used to assess model performance.

## Conclusion
This analysis provides valuable insights into Uber trip patterns, highlighting trends in mileage, trip purposes, and time-based behaviors. Further improvements can be made by incorporating external factors such as weather and traffic data for better predictions.

## Running the Code

To run the analysis locally or on Google Colab, follow these steps:

### 1. Clone this repository:
```bash
git clone https://github.com/your-username/uber_data_analysis.git
cd uber_data_analysis
