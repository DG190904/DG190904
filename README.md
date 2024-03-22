Credit Card Fraud Detection Using Logistic Regression

Overview

This project aims to develop a machine-learning model to detect fraudulent credit card transactions. The dataset used contains features of credit card transactions, and the goal is to train a logistic regression classifier to predict whether a transaction is fraudulent or not.

Dataset

Time: The time elapsed between this transaction and the first transaction in the dataset (in seconds).
- V1-V28: Anonymous features resulting from a PCA transformation to protect user identities. These features may represent various transaction attributes such as transaction amount, location, and type.
- Amount: The transaction amount.
- Class: The target variable indicating whether a transaction is fraudulent (1) or not (0).

Dependencies
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Logistic Regression

Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   
Install the required dependencies:

pip install -r requirements.txt


Usage
1. Run the Jupyter notebook credit_card_fraud_detection.ipynb to train the logistic regression classifier and visualize the results.
2. Ensure that the dataset file credit2023.zip is located in the same directory as the notebook.
3. Follow the instructions in the notebook to load the dataset, preprocess the data, train the model, and evaluate its performance.

Results
The logistic regression classifier achieved an accuracy of 0.7893533580711535 on the test set. A confusion matrix was generated to visualize the model's performance in detecting fraudulent and non-fraudulent transactions.

License
This project is licensed under the MIT License. See the LICENSE file for details.

This README file now briefly describes each feature in the dataset, helping users understand the nature of the data being used for credit card fraud detection.

