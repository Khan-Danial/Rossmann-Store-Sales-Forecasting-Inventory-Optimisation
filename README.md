# Sales Forecasting & Inventory Optimisation for FMCG Retail

## Overview
This project provides a comprehensive, data-driven solution for mid-sized FMCG and Retail companies. By leveraging advanced time series forecasting techniques and inventory optimisation algorithms, the project delivers actionable insights to reduce stockouts and prevent oversupply—thereby increasing profitability and operational efficiency.

Using the **Rossmann Store Sales** dataset from Kaggle, the project demonstrates how historical sales data combined with predictive modeling can transform inventory management practices, paving the way for smarter business decisions and consulting services.

## Problem Statement
Retailers face constant challenges balancing inventory with fluctuating demand. This project addresses those challenges by:
- **Forecasting Sales:** Predicting daily sales trends with high accuracy.
- **Optimising Inventory:** Recommending ideal stock levels to minimize waste and lost sales.
- **Driving Business Impact:** Providing strategic insights that enhance operational efficiency and reduce costs.

## Dataset
- **Source:** Rossmann Store Sales on Kaggle  
  🔗 [Rossmann Store Sales on Kaggle](https://www.kaggle.com/c/rossmann-store-sales)
- **Content:**  
  - Daily sales records for over 1,000 stores
  - **Features:** Store details, promotions, holidays, competition data, sales figures, open/closed status, etc.
- **Usage:** The dataset enables robust time series analysis and serves as a foundation for generating actionable inventory optimisation recommendations.

## Methodology
- **Data Cleaning & Preprocessing:**  
  Raw data is cleansed, missing values are addressed, and data types are converted appropriately. Additional features—such as moving averages, seasonal trends, and promotional indicators—are engineered to enhance model performance.
  
- **Time Series Forecasting:**  
  Advanced models (e.g., ARIMA, Prophet) are applied to predict future sales trends based on historical data. Techniques like backtesting and cross-validation ensure robust model validation.

- **Inventory Optimisation:**  
  Forecast outputs are integrated with optimisation algorithms to suggest optimal inventory levels that align with predicted demand, balancing cost with service levels.

## Tools & Technologies
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, Statsmodels, Prophet, Matplotlib, Seaborn  
- **Development Environment:** Jupyter Notebook and Google Colab for interactive analysis  
- **Version Control:** Git and GitHub for collaborative development and portfolio presentation

## Results & Business Impact
- **Improved Forecast Accuracy:** Enhanced prediction accuracy reduces excess inventory and mitigates stockouts.
- **Operational Efficiency:** Optimised inventory recommendations translate to significant cost savings and improved stock management.
- **Consulting Value:** The insights and methodologies demonstrated here can directly benefit retail clients, showcasing the potential for data-driven consulting services.

## Setup & Installation
To replicate this project on your local machine or in Google Colab, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/sales-forecasting-inventory-optimisation.git
   cd sales-forecasting-inventory-optimisation
