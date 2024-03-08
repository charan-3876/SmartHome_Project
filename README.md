# Smart Home Energy Usage Analysis

This project involves the analysis of energy consumption data from smart home devices. The goal is to identify usage patterns, peak times, and explore opportunities for energy conservation.

## Dataset

The dataset used in this project is the "Appliances Energy Prediction" dataset from the UCI Machine Learning Repository. It contains experimental data used to create regression models of appliances energy use in a low energy building. You can find the dataset here (https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction).

## Key Insights

1. **Usage Patterns**: The analysis revealed distinct usage patterns and peak times for energy consumption. This information can be used to develop strategies for energy conservation.

2. **Predictive Modeling**: Several machine learning models including Logistic Regression, K-Means Clustering, and Gradient Boosting were built and evaluated. These models can be used to predict future energy usage based on historical data.

3. **Anomaly Detection**: The models were also used to identify unusual energy usage patterns. These anomalies could indicate potential issues with the smart home devices.

- Data Mining: Extracted and preprocessed data from the dataset.
- Time Series Analysis: Analyzed energy consumption patterns over time.
- Predictive Modeling: Built and evaluated several machine learning models.
- Anomaly Detection: Identified unusual energy usage patterns.
- Data Visualization: Visualized the data and results using various plots.

**Insights**

1. **Logistic Regression**: The classification report shows that the model has an accuracy of 78%. This means that the model correctly predicted whether the energy usage was high or low 78% of the time. The precision, recall, and f1-score for both classes (0 and 1) are also around 77-78%, indicating that the model performs similarly well on both high and low energy usage instances.

2. **K-Means Clustering**: The clustering results show that the data points have been grouped into three clusters. The cluster averages provide insights into the characteristics of each cluster. For example, Cluster 0 has the highest average energy usage (106.36), followed by Cluster 1 (98.20) and Cluster 2 (92.04). This suggests that homes in Cluster 0 tend to use more energy than those in Clusters 1 and 2. Similarly, you can compare the averages of other features to gain more insights into each cluster.

3. **Gradient Boosting**: The Gradient Boosting Regressor model has an MSE of 6933.25 and an R2 score of 0.307. The MSE indicates that the model's predictions are, on average, approximately 83.27 units (the square root of MSE, also known as RMSE) away from the actual energy usage values. The R2 score indicates that about 30.7% of the variability in the energy usage can be explained by the features in the model. This suggests that while the model has learned some patterns in the data, it is not able to fully capture all the complexities in the data.


This project was a great opportunity to revisit and apply data science concepts in a practical context. In the future, I plan to explore more complex datasets and try out different machine learning algorithms.
