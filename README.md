# Customer-Segementation-with-K-means
Customer segmentation using K-Means groups customers into five distinct clusters based on their annual income and spending score. The clusters represent different customer types such as low income–low spending (budget customers), low income–high spending (value seekers), high income–low spending (potential customers), high income–high spending (premium customers), and medium income–medium spending (average shoppers). This segmentation helps businesses design targeted marketing strategies, improve customer engagement, and maximize profitability by focusing on the most valuable segments.
After applying K-Means Clustering on customer purchase history (Annual Income vs Spending Score), we can identify 5 distinct customer segments:
Cluster 0: Low Income, Low Spending
Customers with limited annual income and very low spending scores.
They rarely purchase high-value items.
Business Strategy: Not a priority segment, but can be targeted with budget-friendly promotions or discounts.

Cluster 1: Low Income, High Spending (Value Seekers)
Customers with low income but surprisingly high spending.
They may spend more than expected, often attracted by discounts or offers.
Business Strategy: Retain with loyalty programs and affordable deals.

Cluster 2: High Income, Low Spending (Potential Customers)
Customers who have high income but low spending scores.
They have purchasing power but are not actively spending.
Business Strategy: Target with personalized marketing, premium offers, and upselling strategies.

Cluster 3: High Income, High Spending (Premium Customers)
Customers with high annual income and high spending scores.
They are the most profitable and loyal customers.
Business Strategy: VIP treatment, exclusive offers, and personalized experiences to maintain loyalty.

Cluster 4: Medium Income, Medium Spending
Customers with moderate income and balanced spending.
Average shoppers forming the middle class of customers.
Business Strategy: Keep engaged with regular offers and seasonal promotions.

📊 Business Insight:
This segmentation helps the retail store to:
Focus marketing campaigns on high-value clusters (Clusters 1 & 3).
Design strategies to convert Cluster 2 (high income but low spending) into premium buyers.
Reduce effort on Cluster 0 since ROI is low.

# Project Overview

This project applies K-Means Clustering to segment retail store customers based on their Annual Income and Spending Score.
The goal is to identify meaningful customer groups such as budget shoppers, value seekers, potential customers, premium customers, and average shoppers.
This segmentation helps businesses design personalized marketing strategies, improve customer experience, and maximize profitability.

# Dataset Description

Source: Kaggle – Mall Customer Segmentation Data

File Used: Mall_Customers.csv

Columns:

CustomerID → Unique customer ID

Gender → Male / Female

Age → Customer’s age

Annual Income (k$) → Customer’s yearly income in thousands

Spending Score (1-100) → Spending behavior score assigned by the mall

For clustering, the key features used are:

Annual Income (k$)

Spending Score (1-100)

# Workflow & Methodology

Data Upload & Cleaning – Load the dataset and check missing values.

Feature Selection – Use Annual Income and Spending Score for clustering.

Data Scaling – Standardize features for better K-Means performance.

Elbow Method – Determine the optimal number of clusters (k).

Model Training – Apply K-Means clustering with chosen k.

Cluster Assignment – Label each customer with a cluster ID.

Visualization – Scatter plot of customers with clusters & centroids.

Insights – Interpret customer groups (budget, premium, average, etc.).

#  Installation

Run this project in Google Colab or locally with Python 3.

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/Customer-Segmentation-KMeans.git
cd Customer-Segmentation-KMeans


Upload the dataset Mall_Customers.csv to your project folder.

Open customer_segmentation.ipynb in Google Colab / Jupyter Notebook.

Run all cells → you’ll get:

Elbow Method plot (optimal clusters)

Cluster visualization with centroids

Cluster insights summary

# Sample Output (Cluster Insights)

Cluster 0 → Low income, low spending (budget customers)

Cluster 1 → Low income, high spending (value seekers)

Cluster 2 → High income, low spending (potential customers)

Cluster 3 → High income, high spending (premium customers)

Cluster 4 → Medium income, medium spending (average shoppers)

# File Structure
Customer-Segmentation-KMeans/
│── customer_segmentation.ipynb   # Main notebook (Google Colab/Jupyter)
│── Mall_Customers.csv            # Dataset (upload separately if not included)
│── README.md                     # Project documentation
│── requirements.txt              # Python dependencies
│── cluster_plot.png              # Sample visualization output

 # Developed By

HARSHITHA PRASAD S G

GITHUB: harshithaprasadprasad

LINKEDIN: https://www.linkedin.com/in/harshitha-prasad-s-g-55a05a257

Machine Learning Internship @ Skillcraft Technology (Task 2)
