# Naive-Bayes-Classifier-ML
Naive Bayes Classifier for Social Network Ads Prediction
Overview
This Python script demonstrates the application of a Naive Bayes classifier to predict whether a user purchases a product based on demographic data from a social network advertising campaign.
Steps and Methodology
1.	Data Preprocessing:
o	Removed the 'User ID' column as it does not contribute to the prediction.
o	Converted categorical variable 'Gender' to numeric format ('Male' -> 0, 'Female' -> 1).
o	Split the dataset into features (X) and the target variable (y).
2.	Data Splitting:
o	Divided the data into training (80%) and testing (20%) sets using train_test_split.
3.	Feature Scaling:
o	Applied Standard Scaling to normalize the features to a standard normal distribution.
4.	Naive Bayes Classifier:
o	Utilized Gaussian Naïve Bayes from sklearn.naive_bayes to build and train the Naive Bayes model on the training data.
5.	Model Evaluation:
o	Assessed the model's performance using accuracy score and confusion matrix metrics.
o	Visualized the confusion matrix to illustrate true positives, true negatives, false positives, and false negatives.
6.	ROC Curve and AUC:
o	Plotted the Receiver Operating Characteristic (ROC) curve to visualize the trade-off between true positive rate (sensitivity) and false positive rate (1-specificity).
o	Calculated the Area Under Curve (AUC) score to quantify the classifier's ability to distinguish between classes.

Conclusion
The Naive Bayes classifier achieved a model accuracy of approximately 0.94. The confusion matrix and ROC curve provide insights into the model's performance, demonstrating its capability to predict whether a user will purchase based on demographic features. Further model tuning or exploration of additional classifiers could potentially enhance predictive accuracy.

