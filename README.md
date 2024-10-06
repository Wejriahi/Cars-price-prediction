# Car Price Prediction Project
This project predicts the prices of used cars in Tunisia using a machine learning model based on data extracted through web scraping from automobiles.tn

#Overview
This project involves web scraping car listings from the automobile.tn website and building a predictive model to estimate car prices based on various features. The project is designed to demonstrate the integration of data collection, cleaning, analysis, and machine learning in Python.

# Table of Contents
Technologies
Getting Started
Web Scraping
Data Preparation
Predictive Modeling
Results
Contributing
License
#Technologies
Python
BeautifulSoup4
Requests
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
# Getting Started
To get started with this project, you'll need to have Python installed on your machine along with the necessary libraries. You can install the required libraries using the following command:

bash
Copy code

pip install --upgrade beautifulsoup4 requests pandas numpy matplotlib seaborn scikit-learn

# Web Scraping
The web scraping is done using BeautifulSoup and Requests. The script collects data on various car features from multiple pages of the automobile.tn website. The following features are scraped:

Name
Mileage
Localite (Location)
Year
Energie (Fuel Type)
Boite (Transmission)
Horsepower
Price
The data is stored in an Excel file named cars_multiple_pages_VF.xlsx.

# Data Preparation
Once the data is collected, the script performs the following steps:

1. Data Cleaning: Handling missing values and converting categorical variables to numerical format using Label Encoding.
2. Exploratory Data Analysis (EDA): Generating visualizations to understand the data distributions and correlations between features.
   
# Predictive Modeling
Various regression models are implemented to predict car prices:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
The models are evaluated based on R² score and explained variance score. The best-performing models will provide estimated prices based on the features.

# Results
The results are summarized in a DataFrame that compares the actual prices with the predicted prices from different models. The predictions can be visualized to understand how closely the models estimate the actual market prices.

# Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.
