# Customer Churn Prediction

## Introduction
This project focuses on predicting customer churn in an e-commerce platform. Customer churn refers to the phenomenon where customers stop doing business with a company or platform. Predicting churn can help businesses take proactive measures to retain customers and improve customer satisfaction.

## Dataset
The dataset used in this project is an Excel file named "E Commerce Dataset.xlsx." It contains various features related to customer behavior, preferences, and interactions with the e-commerce platform.

### Features
- **CustomerID**: Unique identifier for each customer
- **Churn**: Binary variable indicating whether the customer churned or not
- **Tenure**: Number of months the customer has been with the platform
- **PreferredLoginDevice**: Device preferred by the customer for logging in
- **CityTier**: Tier of the city where the customer resides
- **WarehouseToHome**: Distance in kilometers from the customer's warehouse to home
- **PreferredPaymentMode**: Customer's preferred mode of payment
- **Gender**: Customer's gender
- **HourSpendOnApp**: Average number of hours spent on the platform's app
- **NumberOfDeviceRegistered**: Number of devices registered by the customer
- **PreferedOrderCat**: Customer's preferred order category
- **SatisfactionScore**: Customer satisfaction score
- **MaritalStatus**: Customer's marital status
- **NumberOfAddress**: Number of addresses registered by the customer
- **Complain**: Whether the customer has filed a complaint or not
- **OrderAmountHikeFromlastYear**: Percentage increase in order amount from the previous year
- **CouponUsed**: Number of coupons used by the customer
- **OrderCount**: Total number of orders placed by the customer
- **DaySinceLastOrder**: Number of days since the last order
- **CashbackAmount**: Amount of cashback received by the customer

## Libraries and Tools Used
- **Data manipulation**: Pandas, NumPy
- **Data visualization**: Seaborn, Matplotlib, Plotly
- **Exploratory Data Analysis (EDA)**: Missingno
- **Data preprocessing and imputation**: Scikit-learn
- **Machine Learning models**: Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Decision Tree Classifier, Random Forest Classifier, XGBoost, AdaBoost
- **Evaluation metrics**: Accuracy Score, ROC AUC Score, Classification Report, ROC Curve Display, Confusion Matrix
- **Automated machine learning**: PyCaret (commented out)
- **Other**: Warnings (for suppressing warnings), Jupyter Notebook for inline plotting

## Data Preprocessing
- **Missing Values**: Identified and handled missing values in the dataset.
- **Outliers Detection**: Detected and visualized outliers using boxplots and calculated the percentage of outliers in numerical columns.
- **Capping**: Applied capping technique to handle outliers and ensure data integrity.
- **Label Encoding**: Encoded categorical features using Label Encoder from Scikit-learn.

## Exploratory Data Analysis (EDA)
Performed exploratory data analysis to gain insights into the dataset and visualize relationships between variables. Explored associations between various features and customer churn.

## Feature Selection
Identified top features positively and negatively correlated with customer churn. Selected relevant features for model training.

## Imbalance Target Feature
Addressed class imbalance in the target feature (customer churn) using oversampling techniques (SMOTETomek) from the imbalanced-learn library.

## Machine Learning Models
Trained multiple classification models on the preprocessed data to predict customer churn. Evaluated model performance using training and testing accuracy scores. The following models were trained:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## Conclusion
This README provides an overview of the customer churn prediction project, including the dataset, libraries used, data preprocessing steps, exploratory data analysis, feature selection, model training, and evaluation metrics. The goal of the project is to help businesses understand customer churn behavior and take proactive measures to retain customers.
