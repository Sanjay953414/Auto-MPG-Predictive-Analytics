# Fuel Efficiency Prediction using Machine Learning

## Project Overview

This project aims to predict a vehicle's fuel efficiency (Miles Per Gallon - MPG) using various automobile characteristics such as engine displacement, horsepower, weight, acceleration, model year, and origin.

The objective is to help identify the factors influencing fuel consumption and build predictive models that can estimate fuel efficiency accurately.

The project follows an end-to-end data analytics and machine learning workflow including data cleaning, exploratory data analysis, feature analysis, model building, model evaluation, and hyperparameter tuning.

---

## Problem Statement

Predict fuel efficiency (MPG) based on vehicle specifications to understand the factors affecting fuel consumption and build a reliable predictive model.

Business applications include:

* Assisting manufacturers in optimizing vehicle designs
* Supporting fuel consumption analysis
* Identifying performance drivers
* Improving decision-making through data-driven insights

---

## Dataset Information

The project uses the Auto MPG dataset containing vehicle specifications.

### Features

| Feature      | Description                                  |
| ------------ | -------------------------------------------- |
| mpg          | Fuel efficiency measured in miles per gallon |
| cylinders    | Number of engine cylinders                   |
| displacement | Engine displacement                          |
| horsepower   | Engine horsepower                            |
| weight       | Vehicle weight                               |
| acceleration | Vehicle acceleration                         |
| model year   | Year of manufacture                          |
| origin       | Country/region of origin                     |

---

## Project Workflow

### 1. Data Preparation

* Imported dataset
* Inspected data types
* Identified missing values
* Performed data cleaning

### 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand data patterns.

Analysis included:

* Missing value analysis
* Outlier detection using box plots
* Distribution analysis using histograms
* Correlation analysis
* Scatter plot analysis
* Relationship analysis between variables

### 3. Feature Analysis

Studied the impact of vehicle characteristics on fuel efficiency.

Key observations:

* Weight has a strong negative relationship with MPG.
* Higher horsepower generally reduces fuel efficiency.
* Vehicle origin influences fuel efficiency patterns.
* Newer vehicle models tend to be more fuel efficient.

### 4. Model Development

Multiple regression algorithms were implemented and compared.

Models used:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Ridge Regression
* Lasso Regression

### 5. Hyperparameter Tuning

Optimized Random Forest performance using GridSearchCV.

Parameters tuned:

* Number of estimators (`n_estimators`)

### 6. Model Evaluation

Models were evaluated using regression performance metrics.

Evaluation metrics included:

* RMSE (Root Mean Squared Error)
* R² Score

---

## Tech Stack

### Programming Language

* Python

### Libraries Used

#### Data Manipulation

* Pandas
* NumPy

#### Data Visualization

* Matplotlib
* Seaborn

#### Statistical Analysis

* SciPy

#### Machine Learning

* Scikit-learn

---

## Project Structure

```text
Fuel_Prediction.ipynb
README.md
```

---

## Skills Demonstrated

### Data Analysis

* Data Cleaning
* Missing Value Treatment
* Outlier Detection
* Exploratory Data Analysis (EDA)
* Correlation Analysis

### Machine Learning

* Regression Modeling
* Model Comparison
* Hyperparameter Tuning
* Performance Evaluation

### Visualization

* Histograms
* Box Plots
* Scatter Plots

### Business Analytics

* Trend Identification
* Root Cause Analysis
* Data-Driven Decision Making

---

## How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/fuel-efficiency-prediction.git
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook Fuel_Prediction.ipynb
```

---

## Future Improvements

* Deploy the model using Streamlit or Flask
* Build an interactive dashboard
* Implement advanced algorithms such as XGBoost
* Create an automated prediction pipeline

---

## Author

**Sanjay Patil**

Data Analyst | Power BI | SQL | Python

LinkedIn: https://linkedin.com/in/sanjay-patil1995

