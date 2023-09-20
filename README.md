A "loan default predictor" deep learning model is a machine learning system designed to assess the risk of a borrower defaulting on a loan, such as a personal loan, mortgage, or business loan. This type of model is crucial for financial institutions, banks, and lending companies to make informed decisions when approving or denying loan applications. Here's a detailed description of such a model:

Input Data:
The model takes as input a wide range of data related to the borrower and the loan application. This data typically includes:
Personal information: Name, age, gender, address, etc.
Financial information: Income, employment status, credit score, debt-to-income ratio, etc.
Loan-specific details: Loan amount, loan purpose, loan term, interest rate, etc.

Data Preprocessing:
The input data is preprocessed to handle missing values, outliers, and categorical variables. It may also involve standardization or normalization to bring all features to a consistent scale.

Feature Engineering:
The model may create new features or transform existing ones to capture important patterns and relationships in the data. For example, creating a feature that calculates the borrower's debt-to-income ratio.

Neural Network Architecture:
A deep learning model is used, often a neural network, which can be designed with multiple hidden layers. 

Training Data:
The model is trained on a historical dataset that includes labeled examples of loans, indicating whether they defaulted or were successfully repaid. This dataset is used to teach the model to recognize patterns associated with loan defaults.

Loss Function and Optimization:
The model is trained using a loss function that measures the error between its predictions and the actual loan outcomes. Common loss functions for binary classification tasks like this are binary cross-entropy. Optimization algorithms like gradient descent are used to minimize this loss function.

Validation and Testing:
The trained model is validated on a separate dataset to ensure it generalizes well to new data. Performance metrics such as accuracy, precision, recall, F1-score, and ROC AUC are used to assess the model's effectiveness.
