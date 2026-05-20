# Commercial Analysis: Demand Forecast & Customer 360

## Overview

This project is an end-to-end e-commerce analytics and machine learning project focused on customer behavior analysis, churn prediction, and demand forecasting using Customer 360 approaches.

The project utilizes the REES46 E-commerce Dataset to analyze transaction patterns, customer retention behavior, and revenue concentration while developing predictive analytics models to support data-driven business decisions.

This project demonstrates:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Customer 360 Analytics
* RFM Segmentation
* Churn Prediction
* Demand Forecasting
* Business Insight Generation

---

## Business Problem

E-commerce businesses often face several critical challenges:

* High customer churn rate
* Large number of one-time buyers
* Revenue concentration on a small percentage of customers
* Difficulty identifying high-value customers
* Limited visibility into customer purchasing behavior
* Challenges in forecasting future demand

This project aims to solve these issues by building a Customer 360 analytical framework combined with predictive machine learning models.

---

## Objectives

The objectives of this project are:

* Perform Customer 360 analysis
* Analyze customer purchasing behavior
* Identify churn-risk customers
* Build churn prediction models
* Generate business insights from transactional data
* Support demand forecasting strategies
* Improve customer retention understanding

---

## Dataset

### Dataset Used

REES46 E-commerce Dataset

### Main Features

* `customer_id`
* `event_time`
* `category_code`
* `brand`
* `price`
* `event_type`

### Dataset Characteristics

* Raw dataset size: ~2.6 million rows
* Processed dataset size: 562,149 rows
* Observation period: January 2020 – November 2020

---

## Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* LightGBM

### Tools

* Google Colab
* Jupyter Notebook
* Power BI

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

* Removed duplicate records
* Filtered invalid timestamps
* Handled null values
* Cleaned anomalous prices
* Converted datetime features

### 2. Exploratory Data Analysis (EDA)

* Customer purchasing behavior analysis
* Revenue distribution analysis
* Brand & category analysis
* Churn behavior analysis
* Customer segmentation analysis

### 3. Feature Engineering

Generated customer-level features including:

* RFM Features
* Purchase frequency
* Active days
* Customer lifetime
* Average order value
* Behavioral metrics

Final feature matrix contains:

* 20 customer-level features

### 4. RFM Segmentation

Customer segmentation categories:

* Champions
* Loyal Customers
* Potential Loyalists
* At Risk
* Lost Customers

### 5. Churn Labeling

* Observation window: Sep–Nov 2020
* Customers with zero purchases labeled as churned

### 6. Predictive Modeling

Planned models:

* XGBoost
* LightGBM

Prediction tasks:

* Churn Prediction
* Purchase Behavior Prediction
* Demand Forecasting

---

## Key Insights

### Customer Behavior

* Majority of customers are one-time buyers, indicating structurally high churn behavior.
* Churn prediction becomes highly important due to low customer retention.

### Revenue Concentration

* Samsung and Apple contribute disproportionately high revenue compared to other brands.
* Revenue is concentrated within a relatively small customer segment.

### Product Category Analysis

Top transaction categories:

1. Electronics
2. Home Appliances

### RFM Segmentation

* Large portions of customers fall into:

  * Lost
  * At Risk
* Indicates significant retention challenges.

### Correlation Analysis

Strong positive correlations found between:

* Frequency
* Monetary
* Active Days
* Customer Lifetime

Against:

* Target Revenue

Negative correlation observed between:

* Recency
* Churn

---

## Challenges & Solutions

| Challenge                              | Mitigation Strategy                       |
| -------------------------------------- | ----------------------------------------- |
| Large dataset causing memory overhead  | Applied incremental filtering pipeline    |
| Invalid epoch timestamps               | Added explicit year filtering             |
| High null values in category and brand | Filled with 'unknown' labels              |
| Defining churn observation window      | Used 3-month churn labeling window        |
| Anticipated class imbalance            | Planned SMOTE and class_weight strategies |

---

## Dashboard Preview

### Customer 360 Dashboard

(Add your Power BI dashboard screenshot here)

```md
![Dashboard](images/dashboard.png)
```

---

## Future Improvements

Potential future developments:

* Real-time prediction pipeline
* Streamlit deployment
* Recommendation system integration
* Automated retraining pipeline
* Cloud deployment
* Customer lifetime value prediction

---

## Business Impact

This project can help businesses:

* Improve customer retention strategy
* Identify churn-risk customers earlier
* Understand customer purchasing patterns
* Support marketing personalization
* Improve demand forecasting capability
* Optimize revenue generation strategies

---

## Author

**Anandita**
Data Analyst | Data Science & Machine Learning Enthusiast

LinkedIn: [(Add your LinkedIn URL)](https://www.linkedin.com/in/masayuanandita-/)
Email : ananditaprameswari23@gmail.com

---

## License

This project is intended for educational and portfolio purposes.
