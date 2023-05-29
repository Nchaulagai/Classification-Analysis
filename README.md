# Analysis of Shell Bidding Data Set on eBay

This classification analysis focuses on the detection of shill bidding, which is the fraudulent practice of placing fake bids on auction items to artificially inflate their prices. The data set used for this analysis is the Shell Bidding data set from eBay. 

The analysis begins with an Exploratory Data Analysis (EDA) to gain insights into the data and understand its characteristics. Afterward, four different classification techniques are employed to detect shill bidding in the data set:

1. Logistic Regression: A popular linear classification algorithm that models the relationship between the dependent variable and independent variables using a logistic function.
2. Decision Tree Classifier: A non-parametric classification algorithm that constructs a tree-like model by partitioning the data based on feature values.
3. Random Forest Classifier: An ensemble learning method that combines multiple decision trees to improve prediction accuracy.
4. XGBoost Classifier: An optimized gradient boosting algorithm that is highly effective for classification tasks.

For each of these classification techniques, GridSearchCV is used to tune the model's hyperparameters and optimize their performance. The evaluation metrics considered for the analysis include accuracy, confusion matrix, precision, recall, F1 score, and ROC AUC score. These metrics provide a comprehensive understanding of each model's performance in detecting shill bidding.

To validate the findings and ensure the robustness of the models, K-fold Cross Validation is applied. This technique divides the data set into K subsets, trains and tests the models K times, and provides average performance metrics across the folds. By using K-fold Cross Validation, we can assess the generalization capabilities of the models and obtain more reliable results.

Through this comprehensive analysis, we aim to develop effective models for shill bidding detection, enabling eBay and other auction platforms to identify and prevent fraudulent activities, ensuring a fair and trustworthy marketplace for all users.
