Chicago Real Estate Prediction
Overview
This project aims to predict real estate prices in Chicago using machine learning models. It involves data preprocessing, exploratory data analysis (EDA), and training predictive models such as Linear Regression, Random Forest Regressor, and XGBoost Regressor. The dataset includes various features related to property characteristics, including the number of bedrooms, bathrooms, square footage, and past sale prices.

Features
Data Preprocessing: Handling missing values, encoding categorical variables, and normalizing numerical data.
Exploratory Data Analysis (EDA): Distribution analysis, missing data handling, and correlation heatmaps.
Model Training: Comparing different models and evaluating performance based on R² scores.
Feature Importance Analysis: Identifying key factors influencing real estate prices.
Installation
To run this project locally, follow these steps:

Prerequisites
Ensure you have Python 3.7+ installed along with the following dependencies:

bash
Copy
Edit
pip install numpy pandas scikit-learn xgboost matplotlib seaborn jupyterlab
Download and Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Tushar12023/Chicago-Real-Estate-Prediction.git
cd Chicago-Real-Estate-Prediction
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter lab
Run the notebook:

Open chicago-real-estate-prediction.ipynb
Execute the cells in order to preprocess the data and train the models.
Project Structure
php
Copy
Edit
Chicago-Real-Estate-Prediction/
│── chicago-real-estate-prediction.ipynb   # Jupyter Notebook containing the full analysis
│── data/                                  # (Optional) Directory for dataset
│── README.md                              # Project documentation
│── requirements.txt                        # Required dependencies
Results
Linear Regression: Baseline model with R² Score ~ 0.72
Random Forest Regressor: Best performing model with R² Score ~ 0.79
XGBoost Regressor: Moderate performance with R² Score ~ 0.54
The Random Forest Regressor was found to be the most effective model in predicting Chicago real estate prices.

Future Improvements
Enhance feature engineering to capture additional property attributes.
Tune hyperparameters for better model performance.
Explore additional regression models.
