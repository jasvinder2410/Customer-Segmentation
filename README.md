# Customer Segmentation Using K-Means Clustering
## 📜 Project Overview
This project focuses on using K-Means Clustering to segment customers from a mall based on their spending patterns and annual income. The insights derived from this project can help businesses target specific customer groups more effectively.

## 📊 Dataset
- Source: Mall Customers dataset.
- Features:
  1. CustomerID: Unique identifier for each customer.
  2. Gender: Gender of the customer.
  3. Age: Age of the customer.
  4. Annual Income (k$): Customer's annual income in thousands of dollars.
  5. Spending Score (1-100): Score assigned based on spending behavior.

## 🛠 Tools and Libraries
- Python: Programming language used.
- Libraries:
  1. Pandas and NumPy for data manipulation.
  2. Matplotlib and Seaborn for data visualization.
  3. Scikit-learn for clustering and scaling.

## 🚀 Key Steps
- Data Loading and Exploration:
  1. Loaded and explored the dataset to understand its structure and features.
  2. Ensured data was clean and ready for analysis.

- Clustering:
  1. Used the Elbow Method to determine the optimal number of clusters.
  2. Applied K-Means clustering to segment customers.

- Cluster Visualization:
  1. Plotted clusters to interpret customer segments.

## 📝 Key Findings
- Cluster 1 (Green):
  1. Annual Income: Low
  2. Spending Score: High
  3. Description: Budget-conscious customers who spend a lot despite lower income.

- Cluster 2 (Blue):
  1. Annual Income: High
  2. Spending Score: High
  3. Description: Affluent and high-spending customers; likely premium customers.

- Cluster 3 (Yellow):
  1. Annual Income: Low
  2. Spending Score: Low
  3. Description: Customers with limited spending capacity; need more engagement strategies.

- Cluster 4 (Red):
  1. Annual Income: High
  2. Spending Score: Low
  3. Description: Wealthy but conservative spenders.

Cluster 5 (Orange):
  1. Annual Income: Medium
  2. Spending Score: Medium
  3. Description: Average customers who balance income and spending.

## 📈 Results
The project successfully segmented customers into distinct groups based on their spending behavior and annual income. These clusters can help in designing targeted marketing strategies.
