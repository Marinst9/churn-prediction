# E-commerce Customer Churn Prediction (AI/ML)

## Project Overview
This project focuses on predicting customer churn for an e-commerce platform using a **Random Forest Classifier**. By analyzing customer behavior, purchase history, and satisfaction levels, the model identifies individuals at risk of leaving the platform.

## Key Technical Achievements
* **Algorithm:** Random Forest Classifier with balanced class weights to handle imbalanced data.
* **Data Processing:** Cleaned and engineered features for over 96,000 unique customers using **Pandas**.
* **Feature Engineering:** Developed key indicators including `total_spent`, `avg_review_score`, and `total_installments`.
* **Model Validation:** Implemented Train/Test splitting and evaluated performance using Confusion Matrices and Classification Reports.

## Critical Business Insights
Based on the **Feature Importance** analysis (see chart below), the following drivers were identified:
1. **Purchase Value (`total_spent`):** The strongest indicator of loyalty. Higher initial investment correlates with higher retention.
2. **Customer Satisfaction (`avg_review_score`):** A top-3 driver. Declining satisfaction scores serve as a high-precision early warning for churn.
3. **Payment Flexibility (`total_installments`):** Installment plans play a significant role in customer engagement.

### What drives Customer Churn?
![Feature Importance](What%20drives%20Customer%20Churn.png)

## Relevance to ATLETICA
This project demonstrates the ability to turn operational e-commerce data (similar to Shopify and Gorgias exports) into actionable intelligence. This model can be used to:
* Trigger automated win-back email campaigns for "at-risk" customers.
* Identify specific product categories that cause churn due to low review scores.
* Optimize marketing spend by focusing on high-retention customer segments.

## Data Source
The analysis was performed on the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
