# Classification Analysis of Shell Bidding Dataset on eBay

Shill bidding, the act of placing fake bids on an auction item to artificially increase its price, is a concerning issue in online marketplaces like eBay. In this analysis, we aim to perform a detailed classification analysis on the Shell Bidding dataset obtained from eBay. The dataset contains various features that can help us identify instances of shill bidding.

To start with the analysis, we perform Exploratory Data Analysis (EDA) to gain insights into the dataset's structure and characteristics. We explore the distribution of variables, identify outliers, and examine any patterns or relationships between variables. This step allows us to better understand the dataset and make informed decisions during the subsequent analysis.

Next, we address the issue of missing values in the dataset. Missing values can significantly impact the analysis and modeling process. We employ suitable techniques to fill in the missing values, ensuring that the dataset is complete and ready for further analysis.

To gain a comprehensive understanding of the relationships between variables, we construct a Missing Values Ratio (MSNO) matrix. The MSNO matrix visualizes the patterns of missing values, enabling us to identify any systematic patterns or dependencies between variables. This step aids in uncovering potential biases and making informed decisions regarding feature selection and data preprocessing.

To prepare the dataset for classification modeling, we apply the MinMax Scaler. This scaling technique brings all the features within a specific range, preserving the relationships between variables while avoiding any potential biases introduced by different scales.

Moreover, we utilize label encoding to transform categorical variables into numeric representations. This process enables us to incorporate categorical features into our classification models effectively.

For the classification analysis, we employ four popular techniques:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. XGBoost Classifier

To determine the best hyperparameters for each classifier, we employ GridSearchCV, which exhaustively searches through a specified parameter grid to identify the optimal combination of parameters for each classifier. This approach ensures that our models are fine-tuned and yield the best possible results.

To evaluate the performance of our classifiers, we calculate various metrics, including accuracy, confusion matrix, precision, recall, F1 score, and ROC AUC score. These metrics provide insights into the classifiers' effectiveness in accurately predicting instances of shill bidding.

Furthermore, we apply K-fold Cross Validation to validate our findings. This technique splits the dataset into K subsets and performs multiple iterations of training and testing on different subsets. By averaging the results across these iterations, we obtain a more robust evaluation of our models' performance.

In summary, this analysis aims to detect instances of shill bidding in the Shell Bidding dataset obtained from eBay. Through EDA, missing value handling, feature scaling, label encoding, and the application of four classification techniques, we strive to build accurate and reliable models for identifying shill bidding. The evaluation metrics and cross-validation provide a comprehensive assessment of the models' performance and validity.
