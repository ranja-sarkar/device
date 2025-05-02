# Introduction

Predictive maintenance techniques are utilized to assess the condition of operational equipments, allowing for maintenance to be scheduled as needed. This method offers potential cost savings compared to preventive maintenance.

# Problem statement

Development of a supervised machine learning model to predict the likelihood of device malfunction from aggregated IoT data of daily frequency, and minimization of both false positives (FPs) and false negatives (FNs) in the predictions. 


# Data
The data provided is 6.4 MB, clean one with no missing data. The dataset has 12 variables, one of which datetime. The target variable is 'malfunction' and is binary.

# Solution Approach

A logistic regression model is being built to predict if one of the devices/products would fail or not the next day. Few features have been created and added to the dataset for better understanding of the results obtained from the model. And one of the 9 numerical features in the dataset have been eliminated due to redundancy.

Finally, two model hyperparameters namely, solver and decision threshold have been tuned for a comparison of the FPs and FNs in each case.


