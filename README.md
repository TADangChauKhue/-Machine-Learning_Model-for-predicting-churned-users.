# Machine-Learning_Model-for-predicting-churned-users.

Utilizing Python, data wrangling techniques, and machine learning to analyze customer behavior and predict churned users.

## Introduction

An e-commerce company is implementing a project to predict churned users in order to offer targeted promotions and enhance customer retention strategies. Understanding churn behavior and implementing predictive analytics can help the company take proactive actions to reduce customer attrition.

In this project, I use Python to analyze the dataset, explore key patterns of churned users, and build a machine learning model to predict churn. This includes:

•Performing exploratory data analysis (EDA) to identify significant churn indicators.

•Applying data preprocessing techniques.

•Training and evaluating machine learning models to optimize churn prediction.

**1.Business question**

The main objectives of this project are:

•Customer Churn Behavior Analysis: Identifying the behavioral patterns of churned users and providing actionable insights to the company.

•Churn Prediction Model: Building a machine learning model to predict customers who are likely to churn, helping the company take preventive actions.

**2.Dataset**

The dataset consists of customer information, transaction history, and engagement details. Key variables include:

**3.Datasexplore**

To understand customer churn patterns, the dataset was analyzed to answer key questions:

•What are the primary factors influencing customer churn?

•How do customer tenure, gender, payment method, complaints impact churn probability?

Key insights are visualized using Python libraries such as Matplotlib and Seaborn.

**4.Data Preprocessing and Feature engineering**

Before model training, the dataset underwent preprocessing steps:

•Handling missing values

•Encoding categorical variables

•Feature selection based on correlation and importance

•Scaling numerical features

**5.Machine Learning Model**

A machine learning model was developed using the following steps:

**Model Selection**: Evaluated various classification models including:

•Logistic Regression

•Decision tree

•Random Forest Classifier

**Model Training**: Split dataset into training and test sets and trained models using cross-validation.

**Model Evaluation**: Compared model performance based on accuracy, precision, recall, and F1-score.

**Hyperparameter Tuning**: Optimized the best-performing model using GridSearchCV.

**6.Results & Insights**

Identified key churn indicators such as tenure, complaints, prefer order cat and day since last order.

The best-performing model achieved a Balanced Accuracy of 92.03% on the test set, indicating strong predictive capability.

Customers with high complaints and low satisfaction scores were more likely to churn.

Personalized promotions and improved customer support strategies were recommended to reduce churn.

**7.Conclusion**

This project successfully developed a churn prediction model, providing valuable insights into customer behavior. The model can help businesses implement proactive measures to retain high-risk customers, ultimately improving customer loyalty and revenue.

For full project details, refer to the Jupyter Notebook file. 🚀

