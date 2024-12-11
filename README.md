# DSW-Round-2-assignment
## **Overview**
This repository contains a machine learning pipeline for predicting loan repayment behavior, focusing on identifying defaulters. The project covers data preprocessing, training multiple models, evaluating them, and selecting the best one based on key evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

The solution is organized into two key components:
1. **Model Development**: Training and evaluating different classification models.
2. **Model Selection**: Comparing the performance of various models and selecting the best one based on evaluation metrics.

## **Approach**
1. Data Preprocessing
In the preprocessing stage, the data is cleaned and transformed. Missing values are handled, categorical variables are encoded, and numerical features are scaled for optimal model performance. This ensures the data is ready for machine learning algorithms.

2. Model Development
The project evaluates multiple machine learning models, including:

Logistic Regression: A simple and interpretable model for binary classification tasks.

Random Forest: An ensemble learning method that can capture complex relationships in the data.

XGBoost: A gradient boosting model known for its superior performance in handling imbalanced datasets and high accuracy.

K-Nearest Neighbors (KNN): A non-parametric model used for classification tasks based on similarity.


3. Model Evaluation
Models are evaluated on metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. These metrics help identify the model that performs best for loan default prediction, considering the importance of handling imbalanced data.

4. Model Selection and Hyperparameter Tuning
After training and evaluating the models, hyperparameter tuning is applied using GridSearchCV to optimize the model's parameters for better performance. XGBoost was selected as the best model based on its high ROC-AUC score and strong performance across multiple metrics


## **Conclusion**
This project demonstrates an end-to-end machine learning pipeline to predict loan repayment behavior and identify potential defaulters. After evaluating various models, XGBoost was chosen as the best model for loan default prediction

### **Key files:**
1.Eda.ipynb-EDA Analysis

2.model_.py-Preprocessing

3.model_selection.ipynb-Final Selection
