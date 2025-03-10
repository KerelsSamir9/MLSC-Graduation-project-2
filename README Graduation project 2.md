# MLSC-Graduation-project-2
# Customer Segmentation Using Unsupervised Learning

##  Project Overview
This project focuses on segmenting e-commerce customers using unsupervised learning techniques. The goal is to identify different customer groups based on their transaction behavior and provide strategic insights for targeted marketing.

##  Dataset Overview
The dataset consists of multiple tables containing information about:
- **Customers**: Customer demographics.
- **Transactions**: Purchase behavior, coupon usage, and recency.
- **Genders & Cities**: Additional customer attributes.

##  Steps Implemented
1. **Data Preprocessing**:
   - Loaded and cleaned customer and transaction data.
   - Handled missing values (e.g., filling missing `burn_date`).
   - Extracted relevant features: `total_transactions`, `burned_coupons`, `recency_days`.
   
2. **Feature Engineering**:
   - Calculated transaction frequency per customer.
   - Identified recency (days since last transaction).
   - Scaled numerical features for clustering.

3. **Clustering using K-Means**:
   - Used the **Elbow Method** to determine the optimal number of clusters.
   - Applied **K-Means Clustering** and assigned customers to groups.

4. **Cluster Analysis & Insights**:
   - Analyzed cluster characteristics.
   - Visualized group behavior using bar charts.
   - Suggested marketing strategies for each segment.

##  Key Findings
| Cluster | Avg. Transactions | Avg. Coupons Burned | Avg. Recency |
|---------|------------------|---------------------|-------------|
| 0       | Low (~3)         | Low (~1)           | 70 Days     |
| 1       | Medium (~5.6)    | Medium (~2.8)      | 69 Days     |
| 2       | Low (~3)         | Medium (~1.7)      | 404 Days    |
| 3       | High (~8.2)      | High (~4.9)        | 49 Days     |

##  Marketing Strategies
- **Cluster 0**: Encourage engagement via discount campaigns.
- **Cluster 1**: Strengthen retention using loyalty programs.
- **Cluster 2**: Reactivate inactive users with special offers.
- **Cluster 3**: Reward top customers with exclusive deals.


## Conclusion
This segmentation helps businesses optimize coupon distribution, improve customer loyalty, and increase sales through data-driven marketing strategies.

---


