# Project Title : Credit-Card-Default-Prediction-Supervised-Machine-Learning-Classification-Capstone-Project
# Problem Description
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments.

# Steps Involved :
* Importing libraries
* Dataset Inspection
* EDA :
  1. Handling Missing Data
  2. Univariate Analysis
  3. Analysis on Limit Balance
  4. Analysis on Gender, Education and Marriage
  5. Analysis on Age
  6. Analysis on Payment History
* One Hot Encoding
* Handling Class Imbalance : Using SMOTE
* Data Transformation
* Train Test Splitting
* Model Implementation
* Feature Importance On Random Forest Baseline Model
* Feature Importance On XG Boost Optimal Model

# Baseline Model Comparison Table
![image](https://user-images.githubusercontent.com/46549606/172003887-d5644d19-c4e3-487b-8035-2fc96a723f97.png)

# Optimal Model Comparison Table
![image](https://user-images.githubusercontent.com/46549606/172003902-4f5c7974-77d8-406a-b51c-0f17d1b4ffd9.png)

# Conclusion :
* After Basic EDA,
 1. Limit amount was less for Credit Card Defaulters comparative to non defaulters.
 2. Dataset have more females credit card holder,so number of defaulter have high proportion of females.
 3. Credit Card No. of Defaulters as per education from top to bottom : 
University>graduate school>High School>Others
 4. Number of defaulters have a higher proportion of Singles.
* From all baseline models, Random Forest classifier shows highest test accuracy, F1 score and ROC score.
* Baseline model of Random forest and decision tree shows huge difference in train and test accuracy which shows overfitting.
* After cross validation and hyperparameter tuning, XG Boost shows highest test accuracy score of 88.10% and ROC Score is 0.884.
* Thus XG Boost with optimal model is best to predict the credit Card Default
  
