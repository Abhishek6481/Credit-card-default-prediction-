# Credit-card-default-prediction-


# 📖PROBLEM STATEMENT
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments.
# 📖ALGORITHMS USED:
### I. Logistic regressions 
### II. Decision Tree
### III. Random forests 
### IV. XGB Boost
### V. K-Neatest Neighbor 


# 📖Solution Strategy
My strategy to solve this challenge was:

Step 01: Data Description: Use statistics metrics to identify data distributions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

Step 08: Deploy Modelo to Production: Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.
# 📖CONCLUSION
In this assignment, we had to categorize and forecast if a credit card customer is likely to fall behind on their payments. For credit card firms, this issue is crucial since it enables them to spot dangerous borrowers and take the necessary precautions to reduce their losses.

In the dataset, there are around 22% defaulters and 78% non-defaulters.
Compared to women, men default somewhat more frequently.
Customers who are younger and older have greater default rates.
The rate of defaults rises in tandem with the credit usage rate.
Chances of default rise as the number of late payments rises.
Those who have not paid anything in prior months have a greater default rate.
SMOTE was utilized to balance out any data imbalances after data preparation.
For forecasting customer default, the XGBoost model fared best, with the maximum accuracy (0.95), recall (0.84), F1 (0.82), and auc (0.81).
The most crucial factors for forecasting customer default, according to a feature significance analysis employing SHAP values, were PAY_1, Marriage, Education, and so on.

# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
 Abhishek Rathore| Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations
