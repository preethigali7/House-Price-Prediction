# Predicting House Prices with Linear Regression

---

## Project Overview

This project focuses on predicting house prices using the Linear Regression Machine Learning algorithm. The goal is to estimate house prices based on various housing features such as area, number of bedrooms, bathrooms, furnishing status, and other property-related attributes.

The project demonstrates the complete Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and business insights generation.

---

## Objectives

* Analyze housing market data
* Explore relationships between housing features and prices
* Build a Linear Regression predictive model
* Evaluate model performance using regression metrics
* Generate business insights from housing data

---

## Dataset Information

The dataset contains information about residential properties and their corresponding prices.

### Features Include:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Furnishing Status

### Target Variable

* **Price**

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook
* Git & GitHub

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Correlation Analysis
5. Feature Engineering
6. Train-Test Split
7. Linear Regression Model Training
8. Prediction
9. Model Evaluation
10. Business Insights & Recommendations

---

## Exploratory Data Analysis

The project includes:

* Dataset structure analysis
* Statistical summary
* Missing value analysis
* Correlation heatmap
* House price distribution analysis
* Area vs Price analysis
* Bedrooms vs Price analysis

---

## Correlation Analysis

A correlation heatmap was created to identify relationships between numerical features and house prices.

### Key Observations

* Area has a strong positive relationship with house price.
* Number of bathrooms significantly affects property value.
* Furnishing status and amenities influence housing prices.

---

## Feature Engineering

Categorical variables were converted into numerical format using one-hot encoding with:

* `pd.get_dummies()`

This step helps machine learning models process categorical housing features effectively.

---

## Machine Learning Model

### Linear Regression

Linear Regression was used as the primary regression model to predict house prices.

The dataset was divided into:

* Training Set
* Testing Set

using `train_test_split()` from Scikit-Learn.

---

## Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

### Evaluation Metrics Importance

* **MAE** measures average prediction error.
* **MSE** penalizes larger prediction errors.
* **R² Score** measures how well the model explains price variations.

---

## Results

### Key Findings

* House area strongly influences property prices.
* Houses with more bedrooms and bathrooms generally have higher prices.
* Furnishing status significantly impacts housing value.
* The Linear Regression model successfully identified relationships between housing features and prices.

---

## Business Recommendations

* Real estate companies can use predictive models for pricing strategies.
* Property valuation systems can automate price estimation.
* Housing agencies can identify high-value property factors.
* Buyers can better understand pricing trends before purchasing properties.

---

## Business Value

House price prediction systems help:

* Improve real estate pricing accuracy
* Support data-driven investment decisions
* Reduce manual property valuation efforts
* Analyze market trends effectively
* Enhance customer decision-making

---

## Project Visualizations

The project includes:

* Correlation Heatmap
* House Price Distribution
* Area vs Price Scatter Plot
* Bedrooms vs Price Analysis
* Actual vs Predicted Price Graph

---

## Conclusion

This project successfully implemented a Linear Regression model for predicting house prices. The analysis demonstrated how machine learning techniques can estimate property prices using housing features and data-driven insights.

---

## Author

Preethi Gali

---

## GitHub Repository

Add your repository link here after uploading the project.
