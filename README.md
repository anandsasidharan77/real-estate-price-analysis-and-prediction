# Real Estate Price Prediction and Market Analysis

## Overview

End-to-end data science project involving web scraping, data preprocessing, exploratory data analysis (EDA), feature engineering, machine learning model development, and business intelligence dashboarding using Power BI.

---

## Problem Statement

Real estate pricing is influenced by multiple variables such as location, property size, and amenities. Lack of structured and reliable data makes it difficult for buyers and investors to make data-driven decisions.

---

## Objectives

* Build a machine learning model to predict property prices
* Perform exploratory data analysis to identify key price drivers
* Apply feature engineering techniques to improve model performance
* Develop an interactive dashboard for business insights

---

## Skills and Tools

* Python (Pandas, NumPy)
* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning (XGBoost, CatBoost, Scikit-learn)
* Hyperparameter Tuning (Optuna)
* Web Scraping (Selenium, BeautifulSoup)
* Data Visualization (Matplotlib, Seaborn)
* Business Intelligence (Power BI)

---

## Project Workflow

Web Scraping → Data Cleaning → Feature Engineering → Exploratory Data Analysis → Model Building → Hyperparameter Tuning → Data Modeling (Schema) → Dashboard Development

---

## Data Description

### Raw Data

* Scraped real estate data with unstructured fields
* Includes price strings, textual descriptions, and missing values

### Processed Data

* Cleaned and transformed dataset for modeling
* Numeric conversion of price-related columns
* Extracted features such as BHK and area
* Handling of missing values and outliers

### Schema (Dashboard Layer)

* Structured datasets for Power BI dashboard
* Supports data relationships and aggregations
* Optimized for reporting and visualization

---

## Machine Learning

### Models Used

* XGBoost Regressor
* CatBoost Regressor

### Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

### Performance

* Training R²: 0.83
* Testing R²: 0.70

Model shows mild overfitting due to data noise and feature complexity.

---

## Key Insights

* Location and property size are primary drivers of price
* Significant variation in property prices across cities
* Evidence of price saturation in certain regions

---

## Dashboard (Power BI)

* City-level price comparison
* Price distribution analysis
* Identification of investment opportunities
* Interactive filtering and aggregation

---

## Project Structure

```id="r3q7bn"
data/
  raw/
  processed/
    schema/
notebooks/
dashboard/
reports/
assets/
README.md
```

---

## Business Recommendations

* Implement segment-based or region-specific models for improved accuracy
* Improve data collection processes to reduce noise
* Incorporate additional features such as amenities and neighborhood quality
* Use dashboard insights to identify pricing inefficiencies and investment opportunities

---

## Future Enhancements

* Time-series analysis for price trend forecasting
* Deployment as a web application (Streamlit/Flask)
* Integration of external datasets (economic indicators, location data)

---
