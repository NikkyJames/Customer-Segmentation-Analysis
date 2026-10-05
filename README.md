# 🛍️ Customer Segmentation

# 📌 Project Overview

This project applies RFM (Recency, Frequency, and Monetary) analysis and K-Means clustering to segment customers based on their purchasing behavior.

The analysis transforms transactional data into meaningful customer segments that can support targeted marketing, customer retention, personalized promotions, and data-driven business decisions.

This project was completed as part of the Data Analytics Internship at Oasis Infobyte.


# 🎯 Objectives

🧹 Clean and prepare transactional data
👥 Identify unique customers
📅 Calculate customer-level Recency, Frequency, and Monetary metrics
📏 Standardize RFM features
📉 Determine an appropriate number of clusters
🔵 Apply K-Means clustering
📊 Analyze and profile customer segments
💡 Develop actionable marketing recommendations


# 📊 Dataset

The original dataset contained 525,461 transactions.

After data cleaning and preprocessing:

🧹 6,771 duplicate records were removed
❌ Negative quantities were removed
💰 Invalid prices were removed
✅ 400,916 clean transactions remained
👥 4,312 unique customers were identified
The cleaned transaction data was then aggregated at the customer level for RFM analysis.



# 🔄 Data Preparation

The following preprocessing steps were performed:

🔍 Inspected the dataset structure and data quality
🧹 Handled missing customer information
🗑️ Removed duplicate transactions
❌ Removed invalid negative quantities
💰 Removed invalid price values
📊 Aggregated transactions by customer
🧮 Calculated RFM metrics


# 📐 RFM Analysis

RFM analysis was used to measure customer purchasing behavior:

📅 Recency — How recently a customer made a purchase
🔄 Frequency — How frequently a customer made purchases
💰 Monetary — How much a customer spent

These three features were used as the basis for customer segmentation.


# 📏 Feature Scaling

The RFM features were standardized before clustering to ensure that variables with different numerical scales did not disproportionately influence the K-Means algorithm.


# 📉 Determining the Number of Clusters

Two techniques were used to evaluate the appropriate number of customer segments:

# 🔹 Elbow Method

The Elbow Method was used to examine how within-cluster inertia changed as the number of clusters increased.

The results suggested K=5 as a reasonable candidate for segmentation.

# 🔹 Silhouette Analysis

Silhouette Analysis was used to further evaluate cluster quality and separation.

The selected K=5 solution achieved a silhouette score of:

⭐ 0.6140

This indicates reasonably well-separated and meaningful customer segments.



# 🤖 K-Means Clustering

K-Means clustering was applied to the standardized RFM features using 5 customer segments.

👥 Cluster Distribution

Cluster: 0,      1,     2,    3,   4

Customers: 208, 3,053   10    3,   1,038

The resulting clusters revealed distinct differences in customer purchasing behavior.


# 💡 Customer Segment Insights

The customer segments were profiled based on their RFM characteristics to understand differences in purchasing behavior.

These insights can help businesses identify:

💎 High-value customers
🔄 Frequent customers
💤 Customers requiring re-engagement
🎯 Customers suitable for targeted promotions
📈 Opportunities for customer retention

Clusters containing very few customers should be interpreted cautiously and validated with additional data before making broad business decisions.

# 🎯 Marketing Recommendations

Customer segmentation can support targeted strategies such as:
💎 High-value customers: VIP rewards, exclusive offers, and loyalty programs
❤️ Loyal customers: Personalized promotions and retention campaigns
📢 At-risk customers: Re-engagement offers and targeted communication
🎁 Potential customers: Incentives to encourage repeat purchases
📊 Low-engagement customers: Promotional campaigns designed to increase purchase frequency


# 🛠️ Tools & Technologies

🐍 Python
🐼 Pandas
🔢 NumPy
📊 Matplotlib
🎨 Seaborn
🤖 Scikit-learn
📓 Jupyter Notebook


# 📈 Key Takeaways

RFM analysis provides a practical way to understand customer purchasing behavior.
K-Means clustering can identify distinct customer segments from transactional data.
The 5-cluster solution achieved a silhouette score of 0.6140.
Customer segments can support more personalized and targeted marketing strategies.
Very small clusters require additional validation before being used for major business decisions.
Data-driven segmentation can improve customer retention and marketing effectiveness.


# 📝 Conclusion

This project demonstrated how RFM analysis and K-Means clustering can transform transactional data into actionable customer insights.

After cleaning the transaction data, customer-level RFM metrics were calculated and standardized. The Elbow Method and Silhouette Analysis were then used to determine an appropriate number of customer segments.

A 5-cluster K-Means solution was selected, achieving a silhouette score of 0.6140, indicating reasonably well-separated customer groups.

The resulting segments revealed differences in customer purchasing behavior and can support targeted marketing strategies, including customer retention, personalized promotions, re-engagement campaigns, and strategies for high-value customers.

Overall, this analysis demonstrates how customer segmentation can help businesses make more informed, data-driven marketing decisions.



# 🎓 Internship

Organization: Oasis Infobyte
Program: Data Analytics Internship
#OasisInfobyte #OIBSIP



# 👩🏽‍💻 Author

Adenike Adetuberu
