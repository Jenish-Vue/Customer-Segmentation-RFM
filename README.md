# Cleaning and Segmenting Customers for Online International Grocery Retail

This project involves cleaning and segmenting customer data for an online international grocery retail company.
The dataset used for this analysis is from Kaggle's "Grocery Sales Dataset" and contains various CSV files related to customers, sales, products, and more. 
After performing data cleaning and merging, RFM (Recency, Frequency, Monetary) analysis is conducted to segment customers, and various visualizations are used to identify important customer segments.

## Dataset

The dataset consists of the following CSV files:

    categories.csv: Contains product categories.
    cities.csv: Contains city information.
    countries.csv: Contains country information.
    customers.csv: Contains customer details.
    employees.csv: Contains employee details.
    products.csv: Contains product details.
    sales.csv: Contains sales transaction data.

The data is sourced from Kaggle and can be found here:
Kaggle Grocery Sales Dataset

## Steps Involved

    1. Data Cleaning:
        Merging of the individual CSV files (categories.csv, cities.csv, countries.csv, customers.csv, employees.csv, products.csv, and sales.csv) into one comprehensive dataset.
        Handling missing values, duplicates, and ensuring data consistency across different sources.

     2. Data Transformation:
        The merged data is transformed to create meaningful features for RFM analysis. The features include:
            Recency: How recently a customer made a purchase.
            Frequency: How often a customer makes a purchase.
            Monetary: How much money a customer has spent.

     3. RFM Analysis:
        RFM scores are calculated for each customer. These scores are used to rank customers based on their:
            Recency: Time since the last purchase.
            Frequency: Number of purchases over a specified period.
            Monetary: Total spending over the period.

     4.Customer Segmentation:
        Customers are segmented based on their RFM scores, which helps to classify them into different segments (e.g., High-Value, Low-Value, Loyal, At-Risk).

     5.Data Visualization:
        Monetary vs. Recency: A scatter plot to visualize the relationship between customer spending and recency of their purchases.
        Recency vs. Frequency: A scatter plot to show how often customers make purchases in relation to the recency of their last purchase.
        Frequency vs. Monetary: A scatter plot to examine how frequency of purchases correlates with the amount of money spent by customers.

These visualizations help to identify the key customer segments that are most valuable and worth targeting for marketing campaigns.

### Conclusion

This project demonstrates how customer segmentation using RFM analysis can be applied to an online grocery retail business to understand customer behavior and improve marketing strategies.
The insights gained from the analysis can be used to tailor marketing campaigns and drive better business decisions.
