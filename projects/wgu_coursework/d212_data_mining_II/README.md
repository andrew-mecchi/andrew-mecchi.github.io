# **D213 - Data Mining II**

## **Task 1: K-Means Clustering Analysis**

### **Summary** 
The goal of this analysis is to goal of this analysis is to apply the k-means clustering technique on specific features and glean valuable insight relative to customer characteristics and habits. To achieve this goal, features are selected, optimal clusters are explored, and enacted in the model. 

### **Research Question** 
Based on selected features, what clusters can be found using the k-means clustering algorithm and what are the characteristics of those clusters?


### **Analysis Techniques Used:**
- K-Means Clustering
  - Analyzes unlabeled data and create groups (or clusters) with similar characteristics
  - Use elbow method to determine optimal number of clusters (plot inertia vs. k-clusters)
  - Confirm optimal number of k-clusters with plot of silhouette scores
  - Implement standard scaler on selected features
  - Create and use pipeline for model
    - pipeline defined to use standard scaler and k-means algorithm defined with optimal n_clusters
  - Analyze model based on silhouette scores of predicted test set
  <br><br>

## **Task 2: Principal Component Analysis**

### **Summary** 
The goal of this analysis is to successfully reduce the dimensionality of the WGU Telecom dataset. The results of an effective principal component analysis allows for subsequent analysis of the targeted principal components and will assist with further assessment of customer habits which will lead to better, informed decision-making.

### **Research Question** 
Can principal component analysis be used to identify important features that contribute to common characteristics of WGU Telecom subscribers?


### **Analysis Techniques Used:**
- Principal Component Analysis
  - Reduce original dataframe to selected numeric features
  - Identify principal components and fit to covariance matrix
    - Plot heatmap of covariance matrix
- Calculate eigenvalues and show values on a Scee plot
- Calculate total variance explained by principal components
<br><br>

## **Task 3: Market Basket Analysis**

### **Summary**
The goal of this analysis is to implement a market basket analysis of a fictional Telecom company who wants to limit customer churn through an examination of purchase habits and offer promotional sales to retain customers.

### **Research Question**
Can market basket analysis be used to identify what items telecom subscribers frequently purchase together?


### **Analysis Techniques Used:**
- Market Basket Analysis
  - Encode purchase history data with transaction encoder
  - Identify frequent item sets based on support statistic (items frequently purchased together)
- Create rules table of antecedents and consequents and view summary statistics
- Scatter plot of confidence, lift, and support
- Identify top-3 rules 
