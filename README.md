# Customer-Segmentation-for-Hotel-Booking-Analysis
# Project Overview
This project conducted as part of a group assignment for the Machine Learning course in the third semester, focuses on the analysis and prediction of customer behavior in hotel bookings using the Hotel Booking Demand Dataset. The dataset provides comprehensive insights into booking patterns, customer demographics, and financial transactions. Our goal was to apply machine learning techniques to cluster customers into meaningful segments based on their booking behavior, which could help optimize hotel management and marketing strategies.

The project utilizes Python for data analysis and machine learning implementation, with various models used to identify distinct customer clusters. This project emphasizes the use of clustering algorithms to group customers based on similarities, ultimately providing insights that could enhance customer satisfaction and hotel revenue management.

# Case Description
The key problem addressed in this project is to analyze customer booking behavior in resort and city hotels in Portugal and identify distinct customer segments. These segments can help hotels optimize their operations, marketing strategies, and customer services. The dataset includes variables such as:
- Booking details (lead time, stay duration, booking channel)
- Customer demographics (country, number of guests)
- Financial data (average daily rate, deposit type)
- Booking modifications (cancellations, changes)
Through clustering, we aimed to identify patterns in customer behavior and provide actionable insights for the hotels.

# Objectives
- Analyze booking data to uncover patterns and trends.
- Cluster customers based on booking behavior to create distinct segments.
- Evaluate the effectiveness of clustering models using metrics such as silhouette scores.
- Identify key characteristics of each customer segment to support decision-making in hotel management.
- Provide recommendations for revenue management, customer satisfaction, and marketing strategies.

# Project Steps and Features
1. Data Collection and Preprocessing
- The dataset consists of 119,390 rows and 32 columns, covering details like booking time frames, customer demographics, and financial transactions.
- Preprocessing steps included:
  - Handling missing values.
  - Encoding categorical variables using One-Hot Encoding and Label Encoding.
  - Feature scaling using StandardScaler for numerical data.

2. Clustering Model Construction
- Two clustering algorithms were employed:
  - K-Means: A widely used clustering algorithm, suitable for large datasets.
  - Silhouette Score and Elbow Method were used to determine the optimal number of clusters.
- Data was clustered into two customer segments based on the most optimal results from silhouette scores and elbow method.

3. Cluster Evaluation and Interpretation
- The clusters were evaluated based on their distinct characteristics, including booking patterns, cancellation rates, and financial preferences.
- Cluster 1 was identified as more flexible, budget-conscious travelers, while Cluster 2 included well-planned, higher-budget travelers.

4. Results and Insights
- The analysis revealed distinct patterns in customer behavior, such as:
  - Cancellation rates: Cluster 1 showed higher cancellation rates compared to Cluster 2.
  - Booking lead time: Cluster 2 showed longer booking lead times, suggesting more planning.
  - Stay duration: Cluster 1 had shorter stays, potentially business travelers, while Cluster 2 had longer stays.

# Tools
- Programming Language: Python
- Libraries:
  - Pandas: For data manipulation.
  - NumPy: For numerical operations.
  - Matplotlib & Seaborn: For data visualization.
  - Scikit-learn: For implementing machine learning models (K-Means).
  - StandardScaler: For data normalization.

# Challenges
- Data Preprocessing: Handling missing values and encoding categorical data effectively was challenging due to the large number of variables.
- Cluster Determination: Determining the optimal number of clusters required careful analysis using silhouette scores and elbow methods.
- Imbalance in Booking Data: Cancellation rates and lead times varied significantly, impacting the clustering model's results.

# Conclusion
This project successfully clustered hotel customers into two distinct segments based on their booking behavior, providing valuable insights into customer preferences and behavior. The analysis revealed clear distinctions between flexible, budget-conscious travelers and well-planned, higher-budget travelers.

The insights gained from this project can be used by hotels to optimize revenue management strategies, improve customer satisfaction, and design targeted marketing campaigns. Future work could involve extending the analysis to include more sophisticated machine learning models and additional data features
