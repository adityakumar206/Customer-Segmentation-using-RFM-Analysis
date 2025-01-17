Customer Segmentation Using RFM Analysis

Objective
This project focuses on performing RFM (Recency, Frequency, Monetary) analysis on an e-commerce dataset to segment customers into distinct groups. The insights derived from these segments aim to support targeted marketing and customer retention strategies.

Dataset
The dataset used for this project is publicly available on Kaggle: E-commerce Data: https://www.kaggle.com/datasets/carrie1/ecommerce-data. It contains 541,909 records and 8 features spanning customer transactions.

Project Workflow

1. Data Preprocessing
Imported the dataset and handled missing values.
Converted data types and performed initial data cleaning.

2. RFM Calculation
Calculated:
Recency: Days since last purchase.
Frequency: Count of unique invoices per customer.
Monetary: Total spending by a customer.
Compiled results into a DataFrame (rfm_data).

3. RFM Segmentation
Used RFM scores to create customer segments.
4. Customer Segmentation
Implemented KMeans clustering to group customers.
Evaluated clustering quality using:
Elbow Method: Determined optimal number of clusters.
Silhouette Score: Assessed cluster separation and cohesion.

5. Segment Profiling
Analyzed and visualized segments:
Active High-Spenders: Loyal, high-value customers.
Average Buyers: Occasional purchasers.
Elite High-Spenders: Highly engaged, premium customers.
Inactive Low-Spenders: Churned or disengaged customers.

6. Marketing Recommendations
Developed tailored strategies for each segment, including:
Retention campaigns for active customers.
Personalized offers for average buyers.
Win-back campaigns for inactive users.
Highlighted cross-selling, upselling, and engagement strategies.

7. Visualization
Explored customer behavior with:
Recency, Frequency, and Monetary distribution plots.
Cluster visualizations and correlations.
Temporal analyses (hourly, daily, and monthly trends).

Key Insights
Customer Clusters:

Cluster 1: Elite buyers, contributing the highest revenue.
Cluster 2: Average buyers, significant in volume but moderate in spending.
Cluster 3: Low-value, inactive customers.
Time-Based Trends:

Peak order times: Around 3 PM.
High order months: December, indicating holiday season spikes.
Geographical Trends:

Identified top 5 countries by order volume.
Explored correlations between average order value and customer count.

Tools and Libraries
Data Manipulation: pandas, NumPy
Visualization: Matplotlib, Seaborn
Clustering: sklearn
