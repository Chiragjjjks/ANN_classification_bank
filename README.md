# Customer Churn Prediction using ANN

## Overview

This project is an Artificial Neural Network (ANN)-based model for predicting customer churn in a financial institution. The model is trained on a dataset containing customer information, including demographics, account details, and transaction history.
To try out the model - [streamlitApp]((https://annclassificationbank-dlg6uukczpbsbgwypmhjz7.streamlit.app/))
## Dataset

The dataset consists of 10,000 rows and 14 columns, containing the following features:

- **RowNumber**: Index of the row
- **CustomerId**: Unique ID assigned to each customer
- **Surname**: Customer's surname
- **CreditScore**: Customer's credit score
- **Geography**: Country of residence (France, Spain, Germany)
- **Gender**: Customer's gender (Male/Female)
- **Age**: Customer's age
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance of the customer
- **NumOfProducts**: Number of products held by the customer
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated salary of the customer
- **Exited**: Target variable (1 = Churned, 0 = Retained)

## Project Structure

```
├── requirements.txt       # Required Python libraries
├── README.md              # Project documentation
├── .gitignore             # Files to ignore in Git
```

## Installation

### Prerequisites

Make sure you have Python installed. It is recommended to use a virtual environment.

1. Clone the repository:
   ```sh
   git clone https://github.com/Chiragjjjks/ANN_classification_bank
   cd ANN_classification_bank
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Model Architecture

The ANN model consists of the following layers:

- Input Layer: Accepts numerical and categorical features
- Hidden Layers: Multiple dense layers with ReLU activation
- Output Layer: Sigmoid activation for binary classification

## Results

The model achieves an accuracy of approximately **90%** on the test set.

## Author

[Chiragjjjks]((https://github.com/Chiragjjjks))

