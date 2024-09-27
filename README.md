# Retail-customer-segmentation

## Project Overview
This project aims to perform customer segmentation using K-means clustering on an online retail dataset. Customer segmentation helps businesses understand their customer base better by grouping customers into segments based on their purchasing behavior.

## Business Objective
The goal is to:

Analyze and clean the dataset.
Apply K-means clustering to segment customers.
Use the segments to distribute loyalty coupons effectively.

## Dataset
The dataset (Online Retail.csv) includes:

**InvoiceNo**: Invoice number

**StockCode**: Product code

**Description**: Product description

**Quantity**: Quantity purchased

**InvoiceDate**: Date of the invoice

**UnitPrice**: Price per unit

**CustomerID**: Customer identifier

**Country**: Country of the customer

## Tools and Libraries Used
Python

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for data visualization

Scikit-learn for K-means clustering

Jupyter Notebook for interactive analysis

## Steps Involved
### Data Cleaning and Preparation:

Handling missing values and duplicates.

Filtering out cancelled orders and zero-priced items.

### Exploratory Data Analysis (EDA):

Analyzing product sales and customer demographics.

Visualizing purchase patterns by day, month, and hour.

### RFM Analysis:

Calculating Recency, Frequency, and Monetary (RFM) scores for customer segmentation.

Applying log transformation to normalize data.

### K-means Clustering:

Determining the optimal number of clusters using the elbow method.

Applying K-means clustering to segment customers based on RFM scores.

### Interpreting Results:

Analyzing clusters and their characteristics.

Providing recommendations for targeted marketing strategies.

## Insights and Recommendations
Cluster 3 represents highly active and valuable customers who should receive loyalty coupons.

Clusters 1 and 4 include customers who may benefit from festive offers to increase engagement.

Cluster 2 indicates customers at risk of lapsing and should be targeted with special promotions.

## Conclusion
Customer segmentation using K-means clustering enables businesses to personalize marketing efforts effectively. By understanding customer behavior and preferences, businesses can optimize engagement and maximize returns on marketing investments.
