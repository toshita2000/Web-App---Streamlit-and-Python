# Web-App---Streamlit-and-Python
This app uses streamlit library framework to show a web app on machine learning. 
The basic step for running a streamlit app is: -
# streamlit run filename.py
The file runs on a local host
This web app has three machine learning algorithms with its hyperparameters.
# 1. Support Vector Machine 
An SVM model is basically a representation of different classes in a hyperplane in multidimensional space. The hyperplane will be generated in an iterative manner by SVM so that the error can be minimized. The goal of SVM is to divide the datasets into classes to find a maximum marginal hyperplane (MMH).
This web app utilises 2 kernels: - Linear and the other RBF (Radial Basis Function kernel)
SVM ia a great algorithm which has great accuracy
# 2. Random Forest
Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset." Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output.The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.
# 3. Logistic Regression
Logistic Regression is Classification algorithm commonly used in Machine Learning. It allows categorizing data into discrete classes by learning the relationship from a given set of labeled data. It learns a linear relationship from the given dataset and then introduces a non-linearity in the form of the Sigmoid function.


Each of the above algorithms are plotted using three different plot metrics
# 1. Precision Recall Curve
A PR curve is simply a graph with Precision values on the y-axis and Recall values on the x-axis.
# 2. Confusion Matrix
A confusion matrix is nothing but a table with two dimensions viz. “Actual” and “Predicted” and furthermore, both the dimensions have “True Positives (TP)”, “True Negatives (TN)”, “False Positives (FP)”, “False Negatives (FN)”
# 3. ROC curve
ROC is a probability curve for different classes



