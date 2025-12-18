# Telco Customer Churn Analysis

## Project Overview
Customer churn is a critical challenge for telecom companies, as retaining existing customers is more cost-effective than acquiring new ones.  
This project performs **Exploratory Data Analysis (EDA)** on the Telco Customer Churn dataset to identify key factors influencing customer churn and to derive actionable business insights using data visualization.

---

## Objectives
- Analyze customer demographics, service usage, and payment behavior  
- Identify services associated with higher churn rates  
- Visualize churn patterns using clear and interpretable plots  
- Provide data-driven recommendations to improve customer retention  

---

## Dataset Description
- **Dataset Name:** Telco Customer Churn  
- **Number of Records:** ~7,000 customers  
- **Target Variable:** Churn (Yes / No)  
- **Feature Categories:**
  - Customer demographics
  - Internet and value-added services
  - Contract type and payment methods

---

## Tools and Technologies
- Python  
- JupyterLab  
- Pandas (data manipulation)  
- NumPy (numerical analysis)  
- Matplotlib and Seaborn (data visualization)  

---

## Methodology
### Data Understanding and Preparation
- Loaded and inspected the dataset
- Handled categorical features for analysis
- Verified data consistency and structure

### Exploratory Data Analysis
- Univariate analysis using count plots
- Churn-based comparison using hue segmentation
- Service-level analysis using multi-panel subplots
- Stacked bar charts to analyze churn distribution in percentages
- Annotated plots for better interpretability

---

## Key Insights
- Customers without **OnlineSecurity**, **TechSupport**, and **DeviceProtection** show significantly higher churn rates.
- **Fiber optic internet users** exhibit higher churn compared to DSL users.
- Customers subscribed to **multiple or bundled services** tend to have better retention.
- Certain **payment methods** are associated with higher churn risk.

---

## Business Recommendations
- Bundle security and technical support services with internet plans.
- Design targeted retention strategies for Fiber optic customers.
- Promote bundled service subscriptions through discounts and offers.
- Monitor high-risk payment methods and introduce incentive-based retention plans.

---

## Project Structure
