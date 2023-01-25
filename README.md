This readme file explains a project that is designed to predict the probability of default by a borrower. The goal of the project is to generate strategies that can minimize the risk of financial deterioration for the client. The project uses a machine learning algorithm, specifically logistic regression, random forest, and Xgboost, to analyze a bank dataset of clients and make predictions about their risk of default.

The project begins with data preparation and pre-processing, which includes checking for missing values and removing outliers. The next step is encoding concept, which is the process of converting categorical variables into numerical variables so that they can be used in the model. 

The project also includes feature engineering and selection, which involves selecting the most relevant features that can be used to train the model. After feature selection, the next step is scaling the features, which is the process of normalizing the data. This is done to ensure that the model is not affected by the scale of the data. 

Next, the data is balanced, which means that the number of observations in each class is equal.
After data preparation, the model development and model evaluation begins. 

The project uses three different machine learning algorithms: logistic regression, random forest, and Xgboost classifier. Hyperparameter tuning is also performed to optimize the performance of the model. Cross-validation is used to evaluate the model's performance and ensure that it generalizes well to new data. The final accuracy of the model we achieved was 82%.

This project is written in Python and requires specific libraries such as numpy, matplotlib, scikit-learn, seaborn and python 3.9. To run the model on your own system, you will need to clone or download the repo, open command prompt in the downloaded folder, install Jupyter notebook if you haven't and also install xgboost by using pip install xgb in command line prompt or anaconda if you haven’t.

The dataset used in the project can be found on Kaggle at the following link https://www.kaggle.com/datasets/laotse/credit-risk-dataset .

In conclusion, we have built a credit risk model using python and different machine learning algorithms such as logistic regression, random forest and Xgboost classifier. We have also performed hyperparameter tuning and cross-validation. The final accuracy of the model achieved was 82%
