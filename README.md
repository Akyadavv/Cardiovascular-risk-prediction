# Cardiovascular-risk-prediction
# Objective

This classification project aims to predict whether the patient has 10 -year risk of future coronary heart disease(CHD). The information can make patients aware in advance so that they can prevent that from happening. The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors. Following are the steps taken to complete this project:

# Approach:

1. Understanding Data : The given data set had shape of (3390, 17), It had null values, outliers and class imbalance.

2. Data vizualization and story telling: This step is important to know the relationship between our target variable and independent features. It is key to find out underlying trend and patterns which can help business in data driven decision making.

3. Feature engineering and Data preprocessing: this step involves adding new feature to the dataset and prepare dataset by removing null values , removing outliers and by handling calss imbalance, so that I could apply ml models.

4. ML model implementation : Applied different Ml models on the processed dataset and evaluted the metrics.

# Conclusion

In conclusion, the cardiovascular disease classification project aimed to predict the 10-year risk of future coronary heart disease (CHD) in patients using various machine learning models. The models utilized in the project included logistic regression, decision tree, random forest, support vector machine (SVM), and XGBoost boosting algorithm.

After thorough evaluation and comparison of the models, the logistic regression model emerged as the best performer. It achieved a test recall of 0.70 and an accuracy of 0.64. These metrics indicate that the logistic regression model was able to effectively identify the positive cases of CHD and achieve a reasonably accurate overall classification.

The logistic regression model's performance suggests its suitability for predicting the 10-year risk of CHD in patients based on the given set of features. Its recall score of 0.70 indicates that it successfully identified a significant portion of the true positive cases, which is crucial in this medical context. The accuracy score of 0.64 suggests that the model achieved a reasonable overall classification accuracy.
