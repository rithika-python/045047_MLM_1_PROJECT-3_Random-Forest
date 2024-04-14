# COVID-19 Data Classification Project

**Overview:**

This project focuses on classifying COVID-19 data into segments or categories using supervised machine learning techniques such as Decision Trees and Random Forests. The dataset consists of various features such as iso_code, continent, location, date, total_cases, new_cases, new_cases_smoothed, total_deaths, new_deaths, new_deaths_smoothed, total_cases_per_million, new_cases_per_million, new_cases_smoothed_per_million, total_deaths_per_million, new_deaths_per_million, new_deaths_smoothed_per_million.

**Project Objectives:**

Problem Statements
 1. Classification of COVID-19 Data into Segments using Cross-Validation
 2. Classification of COVID-19 Data into Segments using Ensemble Methods
 3. Determination of an Appropriate Classification Model
 4. Identification of Important Features and their Thresholds for Classification


**Data Description:**

Source and Size
 - Data Source: [COVID-19](https://www.kaggle.com/datasets/hosammhmdali/covid-19-dataset)
 - Data Size: 9.78 MB
 - Data Shape: 999990 rows × 18 columns

**Variables:**
1. Categorical Variables
 - iso_code: Country ISO code
 - continent: Continent name
 - location: Country name
 - date: Date of observation

2. Non-Categorical Variables
 - total_cases: Total reported COVID-19 cases
 - new_cases: New reported COVID-19 cases
 - new_cases_smoothed: Smoothed new reported COVID-19 cases
 - total_deaths: Total reported COVID-19 deaths
 - new_deaths: New reported COVID-19 deaths
 - new_deaths_smoothed: Smoothed new reported COVID-19 deaths
 - total_cases_per_million: Total reported COVID-19 cases per million people
 - new_cases_per_million: New reported COVID-19 cases per million people
 - new_cases_smoothed_per_million: Smoothed new reported COVID-19 cases per million
people
 - total_deaths_per_million: Total reported COVID-19 deaths per million people
 - new_deaths_per_million: New reported COVID-19 deaths per million people
 - new_deaths_smoothed_per_million: Smoothed new reported COVID-19 deaths per
million people

**Data Analysis:**

*Descriptive Statistics*
 - Summary statistics for categorical and non-categorical variables
 - Correlation analysis

*Data Pre-Processing*
 - Missing data treatment
 - Encoding categorical variables
 - Outlier detection and treatment
 - Data transformation and scaling
 - Train-test split
   
*Model Building and Evaluation*
1. Base Model (Decision Tree)
 - Metrics: Accuracy
 - Results: Perfect accuracy, efficient training time, moderate memory usage
 - Feature Analysis: Relevant feature - selling_price_mmnorm

2. Comparison Model (Random Forest)
 - Metrics: Cross-validation accuracy, confusion matrix
 - Results: High accuracy, longer training time compared to Decision Tree
 - Feature Analysis: Significant feature - selling_price_mmnorm

3. Results and Insights
 - Model Parameters: Comparison of accuracy and training time between Decision Tree and Random Forest
 - Variable Analysis: Relevant features identified by the models
 - Managerial Insights: Real-life applications and implications of the classification models

4. GitHub Repository
 - The code and documentation for this project can be found in the GitHub repository.

Feel free to ask if you need any further modifications or additions!






