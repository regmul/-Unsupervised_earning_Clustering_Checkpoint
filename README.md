# **Unsupervised Learning: Credit Card Customer Segmentation**
## **Project Overview**

This project applies unsupervised learning techniques to segment credit card customers based on their purchasing behavior and credit limits. By identifying inherent customer groups, the project provides insights for targeted marketing strategies and better resource allocation.

**Dataset**

Source: Credit Card Dataset for Clustering (Kaggle, simplified version)

Description: Contains usage behavior of ~9,000 active credit card holders over a 6-month period.

**Selected Features:**

PURCHASES → total purchase amounts

CREDIT_LIMIT → maximum credit assigned

**Methods Used**

Data Preprocessing

Checked and handled missing values

Removed outliers

Scaled features with StandardScaler

Clustering Techniques

Hierarchical Clustering with dendrograms

Visualization of customer clusters

Evaluation & Interpretation

Scatter plot of clusters

Cluster-wise business insights

**Cluster Analysis**
Cluster 1 (Red)

Profile: Low Purchases + Low-to-Mid Credit Limit

Interpretation: Likely low-value or inactive customers.

Marketing Insight: Provide incentives (discounts, cashback) to encourage engagement.

Cluster 2 (Blue)

Profile: High Purchases + Low-to-Mid Credit Limit

Interpretation: Engaged customers but constrained by limited credit.

Marketing Insight: Offer credit limit increases or premium card upgrades.

Cluster 3 (Green)

Profile: Low-to-High Purchases + High Credit Limit

Interpretation: Premium customers. Some underutilize credit, others are high spenders.

**Marketing Insight:**

High spenders → VIP/loyalty programs to retain.

Low spenders → Encourage usage with exclusive offers/installment plans.

**Message to the Board**

This analysis reveals three key customer segments:

Low-value customers (Red) → Require engagement strategies.

High-potential but constrained customers (Blue) → Upsell with higher credit limits.

Premium/high-credit customers (Green) → Retain with loyalty rewards and personalized offers.

This segmentation enables data-driven marketing and improved profitability strategies.


**Tools & Libraries**

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn, Scipy

**Author**

Regina Mulei
Data Science & Analytics Enthusiast
linkedin- https://www.linkedin.com/in/regina-mulei-892942132/
