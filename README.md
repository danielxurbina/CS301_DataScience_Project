# CS 301 Data Science Project: Analyzing Health Data and Building Predictive Models

## Overview
This project aims to demonstrate practical skills in analyzing complex datasets and building machine learning models. Using health-related data from open data portals, we explore various features, build predictive models, and compare their performance.

## Objectives
- **Perform exploratory data analysis (EDA) on a selected dataset**
- **Train and optimize multiple machine learning models**
- **Evaluate and compare the models based on specific metrics**
- **Discuss findings and potential improvements**

## Dataset
The dataset used in this project is sourced from the NYC Open Data Portal and contains multiple features, both categorical and numerical, related to health indicators. Examples of datasets considered include:
- Air Quality
- 2018 Central Park Squirrel Census
- Harbor Water Quality
- Youth Behavior Risk Survey (High School)
- New York City Leading Causes of Death
- COVID-19 Daily Counts
- NYC Restaurant Inspection Results
- HIV/AIDS Diagnoses by Neighborhood
- NYPD Motor Vehicle Collisions
- School Quality Report

The final dataset selected includes features such as **binge drinking**, **smoking status**, **health insurance coverage**, **self-reported health status**, and various **mortality rates**.

## Exploratory Data Analysis (EDA)
### Feature Insights
We analyzed features to gain insights into their distribution and relationship with the target variable (**No Personal Doctor**). Key features include:
- **Binge Drinking**: Frequency and impact on healthcare access
- **Smoking Status**: Correlation with personal doctor access
- **Health Insurance**: Influence on health service utilization
- **Mortality Rates**: Indicators of healthcare quality and accessibility

### Statistical Summary
For each feature, we provide summary statistics such as **mean**, **standard deviation**, **minimum**, **maximum**, and **quartiles** to understand their distribution and variability.

## Model Training and Optimization
### Selected Models
We trained several models using the features identified during EDA:
- **Linear Regression**: Baseline model for comparison
- **Theil-Sen Regression**: Robust to outliers
- **Ridge Regression**: Addresses multicollinearity
- **Kernel Ridge Regression**: Combines Ridge with kernel tricks for non-linearity

### Optimization Techniques
Each model was optimized using different techniques to enhance performance and robustness. For example, **Ridge Regression** includes a regularization parameter to penalize large coefficients.

## Model Evaluation
### Evaluation Metrics
Models were evaluated using metrics such as:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-Squared (R²)**

### Results
- **Linear Regression**: Provided a baseline performance
- **Theil-sen Regression**: Performed better with high-dimensional data
- **Ridge Regression**: Effective in handling multicollinearity

### Comparison and Discussion
**Linear Regression** emerged as the top performer based on R-squared values. However, **Theil-Sen Regression** showed robustness to outliers, suggesting its utility in certain scenarios.

## Conclusions and Future Work
### Key Findings
- **Binge drinking and smoking status** significantly impact access to personal doctors
- **Health insurance coverage** remains a critical factor for healthcare utilization

### Potential Improvements
- Incorporate larger datasets for more reliable results
- Explore classification models for different healthcare outcomes
- Examine additional factors such as ethnic disparities in health access

## Acknowledgments
This project is part of the **CS 301 Data Science** course. The dataset and tools used were provided by **NYC Open Data** and other open data sources.

## References
- NYC Open Data Portal: [link](https://opendata.cityofnewyork.us/)
- Open Data Discovery Tool: [link](https://dd.akmislam.com/)
