# House Price Prediction using Machine Learning

## Overview

This project focuses on predicting residential property prices using machine learning techniques. The objective is to build a regression model capable of estimating house prices based on various property-related features such as square footage, BHK count, property status, and listing information.

The project follows a complete machine learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction generation.

---

## Dataset Features

The dataset contains information about residential properties, including:

* Property Size (Square Feet)
* Number of Bedrooms (BHK)
* BHK/RK Type
* RERA Approval Status
* Under Construction Status
* Ready-to-Move Status
* Resale Status
* Property Listing Source (Owner, Dealer, Builder)

Target Variable:

* House Price (in Lakhs)

---

## Project Workflow

### 1. Data Cleaning

* Removed duplicate records
* Checked for missing values
* Inspected feature distributions
* Validated dataset quality

### 2. Exploratory Data Analysis (EDA)

* Statistical summaries
* Feature distribution analysis
* House price distribution visualization
* Correlation analysis using heatmaps

### 3. Feature Engineering

Categorical variables were converted into numerical representations:

* Owner → Dealer → Builder
* BHK → RK

Unused geographical and address-based features were removed to simplify modeling.

### 4. Feature Scaling

Standardization was applied to numerical features such as:

* BHK Count
* Square Footage

using StandardScaler.

### 5. Model Development

The following regression models were implemented and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor

### 6. Model Evaluation

Models were evaluated using:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

Performance comparison helped identify the most effective model for house price prediction.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Machine Learning Techniques

* Regression Analysis
* Data Preprocessing
* Feature Engineering
* Feature Scaling
* Ensemble Learning
* Model Evaluation

---

## Results

Multiple regression algorithms were compared to identify the best-performing model for predicting housing prices. Ensemble models such as Random Forest and Gradient Boosting demonstrated improved predictive performance compared to traditional linear approaches.

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Advanced feature engineering
* XGBoost and LightGBM implementation
* Deployment using Flask or Streamlit
* Interactive web application for real-time predictions

---

## Author

Riwas Thapa

Aspiring AI Engineer | Machine Learning Enthusiast | Data Analyst
