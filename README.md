# Loan-Approval-Classification

## Overview

A loan application is used by borrowers to apply for a loan. Through the loan application, borrowers reveal key details about their finances to the lender. The loan application is crucial to determining whether the lender will grant the request for funds or credit.

Handles missing values, modifies data types, and performs exploratory data analysis using visualizations with plotnine and matplotlib.Creates dummy variables for categorical columns using one-hot encoding. Splits the processed data into training and validation sets. Implements XGBoost classifier, grid search with cross-validation for hyperparameter optimization, trains the model, and evaluates its performance. Completes grid search, selects the best hyperparameters, and saves the trained model using joblib.

### Data

- `train_data.csv`: Training dataset with 491 rows and 13 columns.
- `test_data.csv`: Testing dataset with 123 rows and 12 columns.

### Requirements

- `requirements.txt`: Lists the required Python packages and their versions for replication.

The app is built using the Flask web framework and offers an intuitive interface to predict "The loan approval" [Video](https://drive.google.com/file/d/1YTYSeVagjFzNBsmXJxJNcpSp1bynahhI/view?usp=sharing). You can access the live version of this web application [here](https://airlinedelays.azurewebsites.net/).

![Image Alt Text](https://github.com/ThaminduSulakshana/Airline-delay-prediction/blob/b720f0b326667b92f91c274c0a7f424597cdd8ee/Screenshot%20(282).png)
