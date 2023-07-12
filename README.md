# CS 301 Data Science Project

# Project Requirements

One of the main objectives of this course is to help you develop hands-on experience in analyzing complex data and building machine learning models. In this project, you will use a dataset from the open data portals to build at least two machine learning models to demonstrate your technical and analytical skills.

You can use the following tools to get the data for the project:

- NYC Open Data Portal - https://opendata.cityofnewyork.us/
- Open Data Discovery Tool - https://dd.akmislam.com/

In your project, you will complete the following tasks:

## **Task 1: Exploratory Data Analysis**

You will select a dataset from the open data portal that has a minimum of 10 features of which there will be at least one categorical and one numerical features. You will explain the insight of each feature: for example, their distribution,statistics etc and order the features based on their relationship with the target.

## **Task 2: Train Models**

You will train two models with at least three features and explain the optimization algorithms. If there are more than one optimization techniques available, try at least two of them and explain the difference.

## **Task 3: Test and Evaluate**

You will test both models using the test data and explain the evaluation metric with mathematical equations. If there are more than one evaluation metrics available, try at least two of them and explain the difference.

## **Task 4: Make Comparison**

Compare the test results of the both models and discuss the advantages and disadvantages of both models.

## Grading Rubric

- Does the presentation describe the data?
- Does the presentation explain the main objective of the project?
- Does the presentation explain the variations of similar models and specify which one best suits the main objective of the project?
- Does the presentation clearly explain the key findings related to the main objective?
- Does the presentation highlight possible flaws in the model and possible action to revisit the analysis with additional data or different modeling techniques?
- Does the presentation follow a logical order?
- Does the presentation define technical terms in a language appropriate for the target audience?
- Is the length of presentation within the assigned time limit?

# Project Application

## Task 1: Exploratory Data Analysis

- Selecting a Dataset:
    1. Dataset Options (NYC Open Data):
        1. [~~Air Quality~~](https://data.cityofnewyork.us/Environment/Air-Quality/c3uy-2p5r)
        2. [~~2018 Central Park Squirrel Census - Squirrel Data~~](https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw)
        3. [~~Harbor Water Quality~~](https://data.cityofnewyork.us/Environment/Harbor-Water-Quality/5uug-f49n)
        4. [~~Youth Behavior Risk Survey (High School)~~](https://data.cityofnewyork.us/Health/Youth-Behavior-Risk-Survey-High-School-/3qty-g4aq)
        5. [~~New York City Leading Causes of Death~~](https://data.cityofnewyork.us/Health/New-York-City-Leading-Causes-of-Death/jb7j-dtam)
        6. [~~COVID-19 Daily Counts of Cases, Hospitalizations, and Deaths~~](https://data.cityofnewyork.us/Health/COVID-19-Daily-Counts-of-Cases-Hospitalizations-an/rc75-m7u3)
        7. [~~DOHMH New York City Restaurant Inspection Results~~](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j)
        8. [**~~HIV/AIDS Diagnoses by Neighborhood, Sex, and Race/Ethnicity~~**](https://data.cityofnewyork.us/Health/HIV-AIDS-Diagnoses-by-Neighborhood-Sex-and-Race-Et/ykvb-493p)
        9. [~~NYPD Motor Vehicle Collisions Summary~~](https://data.cityofnewyork.us/NYC-BigApps/NYPD-Motor-Vehicle-Collisions-Summary/m666-sf2m)
        10. [**~~Motor Vehicle Collisions - Crashes~~**](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
        11. [**~~NYPD Arrest Data (Year to Date)~~**](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc)
        12. [~~NYPD Shooting Incident Data (Historic)~~](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8)
        13. [**~~NYPD Hate Crimes~~**](https://data.cityofnewyork.us/Public-Safety/NYPD-Hate-Crimes/bqiq-cu78)
        14. [E~~victions~~](https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4)
        15. [~~Parking Violations Issued - Fiscal Year 2023~~](https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2023/pvqr-7yc4)
        16. [**~~School Quality Report~~**](https://data.cityofnewyork.us/Education/2017-2018-School-Quality-Report-District-75-School/qy3b-p2ms)
    2. Dataset Options (Other):
        
        [2021-22-school-quality-guide-elementary-middle-school-data.csv](CS%20301%20Project%206597d7830b124247bf1061cc9a098f87/2021-22-school-quality-guide-elementary-middle-school-data.csv)
        
- Features:
    - Binge Drinking
    - No Health Insurance
    - Smoking Status (current smokers)
    - Self-reported Health Status (excellent/very good/good)
    - Drinks 1 or more sugar-sweetened beverages per day
    - Postneonatal Mortality Rate
    - Did not get needed medical care
    - Infant Mortality Rate
    - Number of Live Births
    - Year
    - Ethnicity*
    - Prevalence*
- Categorical and Numerical Features:
    1. Categorical Features
        1. Year
        2. Ethnicity*
        3. Prevalence*
    2. Numerical Features
        1. Binge Drinking
        2. No Health Insurance
        3. Smoking Status (current smokers)
        4. Self-reported Health Status (excellent/very good/good)
        5. Drinks 1 or more sugar-sweetened beverages per day
        6. Postneonatal Moratality Rate
        7. Did not get needed medical care
        8. Infant Mortality Rate
        9. Number of Live Births
- Explaining the insights of each feature:
    1. ****************************Binge Drinking****************************:
        1. “Binge drinking is defined as five or more drinks on one occasion for men and four or more drinks on one occasion for women in the past 30 days.”
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********: 18.03
            2. **********************Standard Deviation**********************: 1.44
            3. **************Minimum**************: 15.4
            4. **************Maximum**************: 20.9
            5. ****Q1****: 17
            6. ****Q2****: 18.1
            7. ****Q3****: 19.6
    2. **************************************No Health Insurance**************************************:
        1. “The patient does not have Health Insurance”
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    3. ****************Smoking Status (current smokers)****************:
        1. “Smoking status is defined as being a current or former smoker or having smoked less than 100 cigarettes ever.“
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    4. ******************************************************Self-reported Health Status******************************************************: 
        1. “Percentage of adults who report their health is “excellent,” “very good” “good”, or “fair/poor.””
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    5. **************Drinks 1 or more sugar-sweetened beverages per day**************: 
        1. “Respondents were asked how many 12 oz. sugar-sweetened beverages (sodas, iced tea, sports drinks, etc.) they drink per day on average”,
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    6. **********************************Postneonatal Mortality Rate**********************************:
        1. “Number of infant deaths with age between 1 month and 1 year per 1,000 live births in the same calendar year in New York City”
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    7. **************Did not get needed medical care**************: 
        1. “Accumulation of instances where patients did not receive medical care when they needed it.”
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    8. ********Year********:
        1. “Year of death for post-neonatal mortality rate Year of birth for number of live births in New York City (Year study was conducted). "
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    9. ******************************************Infant Mortality Rate******************************************:
        1. "Number of infant deaths under 1 year of age per 1,000 live births in the same calendar year in New York City “
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
    10. ******************************************Number of Live Births******************************************:
        1. “Number of live newborns in New York City.“
        2. **************************************Summary Statistics:**************************************
            1. ********Mean********:
            2. **********************Standard Deviation**********************:
            3. **************Minimum**************:
            4. **************Maximum**************:
            5. ****Q1****:
            6. ****Q2****: 
            7. ****Q3****:
        
- Ordering features based on their relationship with the target:
    1. Target
        1. No personal doctor (Primary Care)
    2. Main Features
        1. Binge Drinking
        2. Smoking Status (current smokers)
        3. Postneonatal Mortality Rate
    3. Features ordered based on the relationship with the target:
        1. Correlation:
            1. **Binge Drinking**: 0.80
            2. **************************************No Health Insurance**************************************: 0.78
            3. ****************Smoking Status (current smokers)****************: 0.77
            4. ******************************************************Self-reported Health Status******************************************************: 0.65
            5. **************Drinks 1 or more sugar-sweetened beverages per day**************: 0.58
            6. **********************************Postneonatal Mortality Rate**********************************: -0.57
            7. **************Did not get needed medical care**************: 0.56
            8. ********Year********: -0.53
            9. ******************************************Infant Mortality Rate******************************************: -0.43
            10. ******************************************Number of Live Births******************************************: 0.42

## **Task 2: Train Models**

- Models Analyzed
    - Linear Regression - Ordinary Least Squares
    - Theil Sen Regression - Multidimensional median
    - Ridge - imposes penalty on the size of the coefficients reducing impact of collinearity
    - Kernel Ridge - Similar to SVR uses Ridge to allow for continuous analysis
- Conclusion and Comparison of the Models
    
    To achieve the main objective, the top-performing models that should be considered are Linear Regression, Theil Sen Regression, and Ridge Regression.
    

## **Task 3: Test and Evaluate**

- Model 1 Testing
    
    The intercept value in this context is 5%, indicating that if a population has a 0% positive report rate on both Binge Drinking and Smoking Status, as well as a 0% Postneonatal Mortality Rate, approximately 5% of the population will report not having a Personal Doctor.
    
    Furthermore, the analysis reveals that for every percentage increase in the population's Binge Drinking rate, approximately 60% of them will not have a personal doctor. Similarly, for every percentage increase in the population's Smoking rate, around 40% of them will not have a personal doctor. Additionally, as the Postneonatal Mortality Rate rises, there is an observed increase in the proportion of people reporting having a personal doctor.
    
- Linear regression model
    
    $No&ensp;Personal&ensp;Doctor = 5.15 + 6 * Binge&ensp;Drinking + .4 * Smoking - 2.6 * Postneonatal&ensp;Mortality&ensp;Rate$
    
- Model 2 Testing
    
    The intercept value in this context is 5%, indicating that if a population has a 0% positive report rate on both Binge Drinking and Smoking Status, as well as a 0% Postneonatal Mortality Rate, approximately 5% of the population will report not having a Personal Doctor.
    
    Furthermore, the analysis reveals that for every percentage increase in the population's Binge Drinking rate, approximately 60% of them will not have a personal doctor. Similarly, for every percentage increase in the population's Smoking rate, around 40% of them will not have a personal doctor. Additionally, as the Postneonatal Mortality Rate rises, there is an observed increase in the proportion of people reporting having a personal doctor.
    
- Theil Sen Regressor
    
  $No&ensp;Personal&ensp;Doctor = .5 + .6 * Binge&ensp;Drinking + .34 * Smoking - 3 * Postneonatal&ensp;Mortality&ensp;Rate$

    

## **Task 4: Make Comparison**

- Test Results Overview
    
    Both models yield comparable results, although Theil Sen regression is expected to perform better for this dimensionality of data. However, due to the absence of outliers, our model's performance is hindered. Additionally, in terms of training time, Linear Regression significantly outperformed Theil Sen regression.
    
- On a Revisit
    
    If we were to revisit the analysis with additional data or different modeling techniques, it would be crucial to have a larger dataset in order to obtain more reliable results. A larger dataset would provide a broader representation of the underlying population, enabling us to make more robust conclusions. However, if the new data exhibits a similar structure and characteristics to the current dataset, it is likely that the modeling techniques would remain largely consistent.
    
    Moreover, with a larger dataset, we could explore additional aspects such as the classification of data and its measurement against ethnic factors. This expanded dataset would allow for more comprehensive analysis, providing insights into the relationship between the variables of interest and different ethnic groups.
    
- Conclusion
    
    In conclusion, after conducting thorough tests, we have determined that the linear regression model outperforms the other models. This conclusion is based on the evaluation of the R-squared value, which indicates the goodness of fit of the model. When applying the linear regression model to predict the 'No Personal Doctor' variable using all of our features, it consistently yields the highest R-squared values compared to the Theil Sen Regression and Kernel Ridge Regression models.
