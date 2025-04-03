# Canadian Airbnb Market Analysis: Descriptive Insights & Occupancy Forecasting Dashboard

[![Project Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)](https://github.com/quachhason/Canadian_Airbnb_Market_Analysis)

## Overview

This project provides a comprehensive analysis of the Canadian Airbnb market across eight major cities.  It combines descriptive data exploration with advanced predictive modeling to understand occupancy trends, key influencing factors, and future occupancy forecasts.  The project delivers actionable insights for Airbnb hosts, potential investors, and tourism stakeholders.

[Link Power BI Dashboard](https://report.onhandbi.com/public/report?token=eyJhbGciOiJIUzI1NiJ9.eyJwdWJsaWNfbGlua19pZCI6MjMxLCJoYXNfcGFzc2NvZGUiOmZhbHNlLCJ0aW1lIjoxNzQwMTU0MjkxfQ.Ayffxi2b4n1IO9-6Cmjb-iwJiiHqVg-UxoDwyMp8QuA)

Location & Property Analysis
![test](https://github.com/quachhason/Canadian_Airbnb_Market_Analysis/blob/main/Images/1.%20Location%20&%20Property%20Analysis.jpg?raw=true)

Pricing & Revenue Analysis
![test](https://github.com/quachhason/Canadian_Airbnb_Market_Analysis/blob/main/Images/2.%20Pricing%20&%20Revenue%20Analysis.jpg?raw=true)

Host & Guest Experience
![test](https://github.com/quachhason/Canadian_Airbnb_Market_Analysis/blob/main/Images/3.%20Host%20&%20Guest%20Experience.jpg?raw=true)

## Key Features

*   **Descriptive Data Analysis:** Interactive Power BI dashboard showcasing Airbnb market dynamics across 8 Canadian cities, visualized through geographic distributions, pricing variations, occupancy rates, and amenity impacts.
*   **Key Factor Identification:**  Identification of key determinants of Airbnb occupancy rates using Random Forest feature importance and SHAP value analysis, highlighting price and host responsiveness as critical factors.
*   **Occupancy Forecasting:**  Development and evaluation of Prophet and XGBoost models for forecasting future Airbnb occupancy rates, considering seasonality and holiday effects.
*   **Comparative Model Evaluation:**  Benchmarking of Prophet and XGBoost model performance using MAE, RMSE, and MAPE metrics, providing guidance for model selection based on forecasting goals.
*   **Actionable Recommendations:**  Data-driven recommendations for dynamic pricing strategies, amenity optimization, and host training to maximize occupancy and revenue.

## Technologies Used

*   **Python:** Core programming language for data preparation, cleaning, feature engineering, modeling, and evaluation.
*   **Pandas:** Data manipulation and analysis.
*   **NumPy:** Numerical computing.
*   **Scikit-learn:** Machine learning algorithms (Random Forest), model evaluation metrics, and data splitting.
*   **Prophet:** Time-series forecasting library.
*   **XGBoost:** Gradient boosting library.
*   **Matplotlib & Seaborn:** Data visualization in Python.
*   **Power BI:** Interactive dashboard creation and visualization.
*   **Google Colab:** Cloud-based environment for development and execution.

## Data Sources

*   **Inside Airbnb:** Publicly available Airbnb datasets for 8 major Canadian cities, covering four seasonal time periods (Dec 2023, Mar 2024, Jun 2024, Sep 2024). Datasets include `listings.csv` and `calendar.csv` files for each city and period.

## Methodology

1.  **Data Collection & Preparation:** Data acquisition from Inside Airbnb, cleaning, integration, and preprocessing of Listings and Calendar datasets for 8 cities.
2.  **Data Cleaning & Feature Engineering:** Extensive data cleaning, handling missing values and outliers, and engineering features related to time, amenities, host characteristics, and location in Python.
3.  **Exploratory Data Analysis (EDA):**  Uncovering key trends and patterns in Airbnb occupancy, pricing, and host/guest behavior using Python visualizations and statistical analysis.
4.  **Power BI Dashboard Development:** Designing and implementing an interactive dashboard to visualize descriptive analytics findings for stakeholder exploration.
5.  **Predictive Modeling (Prophet & XGBoost):**
    *   XGBoost: Training a Random Forest Regressor to identify key factors influencing occupancy using feature importance and SHAP values.
    *   Prophet: Building and evaluating a Prophet time-series model to forecast future monthly occupancy rates, incorporating seasonality, holiday effects, and regressors.
  
![test1](https://github.com/quachhason/Canadian_Airbnb_Market_Analysis/blob/main/5.%20Modeling%20&%20Advanced%20Analysis/4.%20Forecasted%20Occupancy%20Rates%20for%20Toronto.png?raw=true)

6.  **Model Evaluation & Comparison:**  Rigorous evaluation of both Prophet and XGBoost models using appropriate metrics (MAE, RMSE, MAPE) and cross-validation to assess forecasting accuracy and identify model strengths and weaknesses.
![test1](https://github.com/quachhason/Canadian_Airbnb_Market_Analysis/blob/main/Images/4.%20Model%20Performance%20Comparison.jpg?raw=true)

## Key Findings

*   **Price, host responsiveness, and accommodation size are key drivers** of Airbnb occupancy rates in Canada.
*   **Summer is the peak season**, with Vancouver, Toronto, and Victoria exhibiting the highest occupancy rates.
*   **Listings with essential amenities (WiFi, parking, AC)** and **responsive Superhosts** achieve significantly higher occupancy and guest satisfaction.
*   **Prophet provides strong overall occupancy forecasts**, while **XGBoost excels in predicting holiday and weekend occupancy surges.**
*   **Dynamic pricing, amenity optimization, and proactive host training** are key recommendations for maximizing Airbnb success in the Canadian market.

## Repository Contents

*   `1. Data Preparation (Load & Merge).ipynb`: Jupyter Notebook for data loading, merging, and preparation.
*   `2. Data Cleaning & Feature Engineering.ipynb`: Jupyter Notebook for data cleaning and feature engineering processes.
*   `3. Exploratory Data Analysis (EDA).ipynb`: Jupyter Notebook for Exploratory Data Analysis and visualization.
*   `4. Power BI Dashboard for Visualization`: Power BI for Exploratory Data Analysis and visualization.
*   `5. Modeling & Advanced Analysis.ipynb`: Jupyter Notebook containing code for feature importance analysis, Prophet and XGBoost model building, evaluation, and forecasting.
*   `all_listings.csv`, `all_calendars.csv`, `cleaned_listings_v2.csv`, `cleaned_calendars_v2.csv`, `daily_metrics.csv`: Processed data files (or describe data format and source if data files cannot be shared).
*   `Airbnb Canada Occupancy Analysis Dashboard - Power BI.pbit`: Power BI Dashboard template file.
*   `README.md`: This README file.

## How to Run

1.  For Python Notebooks: Open each `.ipynb` notebook sequentially in Google Colab or Jupyter Notebook and run cells to reproduce data preparation, analysis, modeling, and forecasting steps. Ensure data files (or appropriate data access) are available in the specified paths.
2.  For Power BI Dashboard: Open `Airbnb Canada Occupancy Analysis Dashboard - Power BI.pbit` template file in Power BI Desktop to explore the interactive dashboard.

## Author

*   Son Quach
*   My Contact Information: quachhason.96@gmail.com
*   [LinkedIn Profile URL](https://www.linkedin.com/in/quachhason/)
