# **D208 - Predictive Modeling**

## **Task 1: Multiple Linear Regression Analysis**

### **Summary** 
The primary goal of the analysis is to use multiple regression analysis to ascertain a possible predictive model that can assist the hospital(s) in identifying cases related to the patient length of stay. Implementing a backward feature reduction strategy to the “kitchen sink” approach will remove extraneous explanatory variables and produce a statistically significant equation that can accurately forecast the response variable.

### **Research Question** 
What are the most common features related to prolonged stays (increased Initial Days) of patients?


### **Analysis Techniques Used:**
- Multiple Linear Regression
  - Backward feature reduction method using p-values (below 0.05) and variance inflation factor (below 10)
  - Calculate predicted values and residuals
  - Visualize residual plots
    - Histogram
    - Scatter plot with trendline
    - QQ-plot to observe distribution of residuals
  - Calculate Residual Standard Error (RSE)
  - Compute model accuracy 
  - Calculate R-squared values
- Data Processing
  - Remove statistical outliers
    - Z-scores --- normally distrinutions
    - Inter-quartile method --- skewed distributions
  - Normalize cleaned data distributions using log transformations
  - Encode categorical data using dummy variables
  - Scale data using MinMax scaler   
<br><br>
  
## **Task 2: Logistic Regression Analysis**

### **Summary** 
The primary goal of the analysis is to design a predictive model that can accurately identify cases related to the patient readmission. Readmission cases are the targeted response variable and an array of categorical and continuous variables will be included in the initial regression model. The inclusion of a backward feature selection will refine the model’s accuracy until a statistically significant equation yields an accurate prediction of readmissions.

### **Research Question** 
What are the most common features related to prolonged stays (increased Initial Days) of patients?

### **Analysis Techniques Used:**
- Logistic Regression
  - Backward feature reduction method using p-values (below 0.05) and variance inflation factor (below 10)- Calculate predicted values from trained model
- Confusion matrix of actual vs. predicted values
- Calculate accuracy of classifications
-  View model summary
-   Calculate explanatory variable coefficients
-    Calcualte odds ratio and odds percentage
- Data Processing
  -  Calculate and visualize contingency tables/crosstabs of categorical data
  -  Remove statistical outliers
    -  Z-scores --- normally distrinutions
    -  Inter-quartile method --- skewed distributions
  - Encode categorical data using dummy variables
  - Scale data using MinMax scaler
