# credit-risk-classification

For this assignment, the code is performing logistic regression on a loan dataset to classify loans as either low-risk or high-risk and evaluating the model's performance using a confusion matrix and classification report.

Modules were imported for handling numerical computations, data manipulation and file paths:
Numpy, pandas and Path
Confusion_matrix and classification report from sklearn.metrics for evaluating the model's performance.

Data Separation & Splitting:
The target variable (y) is separated from the feature set (x).
Y represents the loan status while x contains the remaining columns (features) after dropping 'loan_status'
The data is then split into testing and training sets.

Logistic Regression Model:
The model is instantiated and trained on the training data and predicts the outcomes of the test data.

Confusion Matrix:
The confusion matrix is generated to compare the actual vs. predicted values, showing how well the model classified the loans as either 'healthy' (low risk) or 'non-healthy' (high-risk) and is displayed as a data frame.

Classification Report:
A report is printed to provide detailed metrics (precision, recall, f1-score, and support) for the model's performance.
