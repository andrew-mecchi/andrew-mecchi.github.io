# **D209 - Data Mining I**

## **Task 1: K-Nearest Neighbor Classifier Analysis**

### **Summary** 
The primary goal of the analysis is to design an algorithm using the k-nearest neighbors (KNN) classifier and refine its performance with quantitative metrics suited to improve predictive accuracy. Implementing Select K Best as a feature selection method identifies the most suitable predictive features to include in the model. These selected features build the model and are optimized through hyperparameter analysis using GridSearhCV. The grid search results aid in the design of the final, optimized machine learning model.  

### **Research Question** 
Can the k-nearest neighbor classifier be used to accurately predict patient Readmissions?


### **Analysis Techniques Used:**
- K-Nearest Neighbor Classification
  - Hyperparameter tuning using GridSearchCV
- Select K Best for feature selection
- Compute confusion matrix and visualize
- Performance Calculations: Accruacy, Precision, Sensitivity/Recall, Specificity
- Classificaiton report
- Plot ROC curve
- Calculate ROC-AUC score
<br><br>
  
## **Task 2: Random Forest Regressor Analysis**

### **Summary** 
The primary goal of the analysis is to design an accurate predictive model using the random forest regressor. Addressing Initial Days identifies the target response variable while explanatory variables are identified through the feature selection method using Select K Best. These selected features define the building blocks of the predictive model and metrics are optimized through hyperparameter analysis using GridSearhCV. The results of the grid search tune the parameters of the random forest regressor and augment the performance of the machine learning model.

### **Research Question** 
Can a Random Forest regressor accurately predict Initial Days (length of hospital stay)?

### **Analysis Techniques Used:**
- Random Forest Regresor
  - Hyperparameter tuning using GridSearchCV
- Select K Best for feature selection
- Performance Calculations: R-squared, mean absolute error (MAE), mean squared error (MSE), root mean squared error (RMSE), accuracy
- Visualize decision tree with random forest best estimators
- Identify and plot feature importances
