# Customer Revenue Prediction
This is a machine learning project that predicts the total revenue generated by customers for an online retail store based on their demographic information, purchase history, and website activity. The goal of this project is to help the store's marketing team better understand and target high-value customers.

# Getting Started
To use the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in requirements.txt. You can do this using pip by running pip install -r requirements.txt.
3. Download the dataset from [https://www.kaggle.com/c/ga-customer-revenue-prediction/data] Kaggle and place it in the data folder.
4. Run the main.py file to train the model and generate predictions.
# Dataset
The dataset used in this project is the Google Analytics Customer Revenue Prediction dataset from Kaggle. It contains anonymized information about customers' website activity, demographic information, and transaction history. The dataset is split into a training set and a test set, with the goal being to predict the natural logarithm of the sum of all transactions per user.

# Model
The machine learning model used in this project is a Gradient Boosting Regressor, implemented using scikit-learn. The model is trained on the training set and validated using the test set. The performance metric used is root mean squared error (RMSE).

# Results
The best model achieved an RMSE of 1.68 on the test set, which indicates that the model is able to predict the natural logarithm of the sum of all transactions per user with reasonable accuracy.

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

License
This project is licensed under the MIT License - see the LICENSE file for details.
