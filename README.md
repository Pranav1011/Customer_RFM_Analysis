📖 Project Overview

Customer segmentation is crucial for businesses to tailor their marketing strategies effectively. This project applies RFM (Recency, Frequency, Monetary) Analysis on an E-Commerce dataset to segment customers based on their purchasing behavior.

Using data preprocessing, RFM metric calculation, clustering techniques (K-Means), and visualization, we derive actionable marketing insights for businesses.

🎯 Objectives
	•	Perform RFM Analysis to derive customer segments.
	•	Apply clustering techniques (K-Means) to group similar customers.
	•	Generate visual insights for better interpretability.
	•	Provide marketing recommendations based on segment characteristics.

 📌 Methodology

The analysis follows a structured workflow:
	1.	Data Preprocessing
	•	Clean and format data, handling missing values.
	•	Identify and address inconsistencies in product descriptions.
	•	Handle missing CustomerID (24.93%) and Description (0.27%).
	2.	RFM Metrics Calculation
	•	Recency: Days since last purchase.
	•	Frequency: Number of orders per customer.
	•	Monetary: Total spending by each customer.
	3.	RFM Segmentation
	•	Assign RFM scores and generate a unified score.
	•	Categorize customers into distinct segments.
	4.	Clustering Analysis
	•	Apply K-Means Clustering to group customers.
	•	Determine the optimal k value using Elbow Method.
	5.	Segment Profiling
	•	Analyze customer segments and their characteristics.
	6.	Visualization
	•	Generate graphs, heatmaps, and visual insights.

 📊 Key Analyses and Findings

We answered critical business questions to understand customer behavior:

🔹 Data Overview
	•	Dataset Size: Number of rows and columns.
	•	Column Descriptions: Understanding data attributes.
	•	Time Period Covered: Analyzing temporal trends.

🔹 Customer Analysis
	•	Number of Unique Customers.
	•	Order Distribution per Customer.
	•	Top 5 Customers by Order Count.

🔹 Product Analysis
	•	Top 10 Most Frequently Purchased Products.
	•	Average Product Price.
	•	Most Profitable Product Category.

🔹 Time-Based Trends
	•	Peak Order Times (Day of Week & Hourly Trends).
	•	Seasonal Trends in Purchasing Behavior.
	•	Average Order Processing Time.

🔹 Geographical Trends
	•	Top 5 Countries by Orders.
	•	Customer Country vs. Order Value Correlation.

🔹 Payment Insights
	•	Common Payment Methods.
	•	Payment Method vs. Order Value Relationship.

🔹 Customer Behavior & Lifecycle
	•	Average Customer Lifespan (First to Last Purchase).
	•	Segmenting Customers by Behavior Patterns.

🔹 Returns & Refunds
	•	Percentage of Orders with Returns.
	•	Correlation Between Product Category & Returns.

🔹 Profitability Analysis
	•	Total Profit Generated.
	•	Top 5 Most Profitable Products.

🔹 Customer Satisfaction
	•	Analysis of Customer Feedback & Ratings.
	•	Sentiment Trends in Feedback (if available).

 🛠️ Tech Stack
	•	Programming Language: Python
	•	Libraries Used: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
	•	Clustering Algorithm: K-Means

 📢 Key Takeaways & Business Recommendations
	•	Target High-Value Customers: Retain high RFM score customers through loyalty programs.
	•	Re-Engage Dormant Customers: Offer discounts to customers with low recency scores.
	•	Optimize Product Recommendations: Suggest frequently purchased products to relevant segments.
	•	Seasonal Promotions: Capitalize on peak order times with targeted campaigns.
