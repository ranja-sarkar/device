# Introduction
Predictive maintenance techniques are utilized to assess the condition of operational equipments, allowing for maintenance to be scheduled as needed. This method offers potential cost savings comapred to preventive maintenance.

# Problem statement
Development of a supervised machine learning model to predict the likelihood of device malfunction from aggregated IoT data of daily frequency, and minimization of both false positives (FPs) and false negatives (FNs) in the predictions. 


# Data
The data provided is 6.4 MB and a clean one with no missing data. The dataset has 12 variables, one of which datetime. The target variable is 'malfunction' and is binary.

# Solution Approach
A logistic regression model is being built to predict if one of the devices or products would fail or not the next day. Few features have been created and added for better understanding of the data as well as the results obtaiined from the model. And one of the 9 numerical features in the dataset have been eliminated due to redundancy.

Finally, two model hyperparameters namely, solver and decision threshold have been tuned for a comparison of the false positives and false negatives in each case.

---

# Alternative
An ensemble model like Random Forest or a non-parametric model like kNN could also have been attempted for the classification prediction. As an example of Random Forest classifier, if you're interested check this out that I had tried with a different dataset sometime back:

https://colab.research.google.com/drive/1PewlbvMAQ8S9YXMz471Rw03vcbs9w5Qd

# Conclusion
A more complex neural network (deep learning algorithm) might as well be tried out for the present problem. However, it is always good to start with a simple baseline. Simple algorithms like logistic regression are tested wnd working just fine since ages for various classification problems and are more interpretable and easy to handle in production.

