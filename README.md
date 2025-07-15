
# COVID-19 Vaccination Trend Analysis Across USA Countries.

# Project Title:

"Trends and Patterns of COVID-19 Vaccination Across U.S. Counties using Machine Learning"


# Introduction

This project explores the distribution and growth of COVID-19 vaccination across counties in the United States using real-world data. It leverages data analysis and machine learning techniques to identify patterns, forecast vaccine distributions, and evaluate predictive models.

# Aim / Objective

1) To analyze COVID-19 vaccination trends over time across different U.S. counties.

2) To build regression models that can predict cumulative vaccine doses based on features like location, time, and vaccination history.

3) To visually represent the progress and effectiveness of vaccine distribution efforts.

4) To evaluate different ML algorithms and choose the best performing one for forecasting vaccine trends.

# Dataset

Dataset source: https://data.chhs.ca.gov/dataset/vaccine-progress-dashboard

#Type: 
.csv file,  

Row: 13, Column: 110857.

# Steps Performed in project.

##  Data Cleaning & Preprocessing

1) Converted date formats

2) Handled missing values.

3) Extracted year, month, day from dates

4) Removed duplicates and detected outliers using IQR

5) Encoded categorical variables (county, california_flag)

6) Scaled numerical columns using Min-Max normalization

##  Exploratory Data Analysis (EDA)

7) Summary statistics & correlation heatmap

8) Distribution of vaccination status (Fully, Partially, Not Vaccinated)

9) Top 10 counties by number of fully vaccinated individuals

10) Year-wise and Month-wise vaccination progress charts

## Model Building and Evaluation.

11) Used Linear Regression, Decision Tree, and Random Forest Regressor

12) Target: cumulative_total_doses

13) Evaluated models using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score (Accuracy of the model)

# Observations & Findings

1) Random Forest Regressor provided the best results with R² = 1.0 and minimal prediction errors.

2) The majority of counties had fully or partially vaccinated populations; few remained not vaccinated.

3) Counties with the largest populations showed significantly higher vaccination numbers.

4) Vaccination trends increased consistently from the beginning of the timeline to the latest date.

# List of Visualizations Included in Project.

1) Correlation Heatmap

2) Pie chart of vaccination status

3) Top 10 counties by vaccination

4) Monthly and yearly vaccination progress charts

5) Model performance comparison bar chart

6) Actual vs Predicted scatter plot for best model

# ML Model performances:

1) Random Forest	5,278.38 (MAE)	1.84 × 10⁹(MSE)	1.0000(R2)

2) Decision Tree	5,387.62 (MAE)	2.07 × 10⁹(MSE)	1.0000(R2)

3) Linear Regression	566,800.29(MAE)	4.96 × 10¹²(MSE)	0.9752 (R2)

# Result: 
Random Forest was selected as the final model due to its low error and high accuracy.

# Conclusion

This project successfully demonstrated how machine learning can be applied to real-world health data to identify patterns and make predictions. 
The analysis gave a clear view of how vaccine rollout progressed in different regions and provided a predictive framework for future planning.



