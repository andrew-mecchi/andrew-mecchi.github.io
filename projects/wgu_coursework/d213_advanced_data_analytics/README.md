# **D213 - Advanced Data Analytics**

## **Task 1: Time Series Analysis**

### **Summary** 
The goal of this analysis is to create an ARIMA Time Series Analysis and project future revenues based on previous trends.

### **Research Question** 
Through the use of a time series analysis of the previous two-years of data, can daily revenues for the next two quarters (Q1 & Q2) be accurately forecasted?

### **Analysis Techniques Used:**
  - ARIMA
    - Model orders defined using autocorrelation (ACF) and partial autocorrelation (PACF) plots
  - Revenue forecast plot based on ARIMA model
  - Calculate RMSE of model
  - Dickey-Fuller test for stationarity wtih seasonality, decomposition, and spectral density plots
  <br>

## **Task 2: Sentiment Analysis**

### **Summary** 
The goal of this analysis is to use Natural Language Processing to determine customer sentiment based on reviews from Amazon, IMDB, and Yelp.

### **Research Question** 
Can the sentiment of a customer review be accurately predicted as positive or negative from a trained model using Natural Language Processing (NLP) and Recurrent Neural Networks (RNN)?

### **Analysis Techniques Used**
  - Build Sequential Model using TensorFlow
  - Model Preperation
    - Tokenize using TensorFlow
    - Vectorize text to numeric values
    - Pad sequences for uniform lenght of vectors 
  - Text Preprocessing
    - Remove puncutation
    - Remove stop words
    - Tokenize text
    - Lemmatize text
    - Remove numeric values
  - Model Evaluation
    - Plots of model accuracy and value loss
    - Confusion Matrix
    - Calculate accruacy, precision, sensitivity/recall, specificity
      




