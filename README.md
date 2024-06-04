# Bati-Bank-Credit-Scoring

## Overview

Bati Bank, a leading financial service provider, is partnering with an eCommerce company to enable a buy-now-pay-later service. As an Analytics Engineer at Bati Bank, you have been assigned the task of creating a Credit Scoring Model using the data provided by the eCommerce platform.

## Business Need

The project aims to build a credit scoring model that can:

1. Define a proxy variable to categorize users as high-risk (bad) or low-risk (good).
2. Select observable features that are good predictors of the default variable.
3. Develop a model that assigns risk probability for a new customer.
4. Develop a model that assigns credit score from risk probability estimates.
5. Develop a model that predicts the optimal amount and duration of the loan.

## Data and Features

The data for this challenge can be found on Kaggle: [Xente Challenge | Kaggle](https://www.kaggle.com/competitions/xente-challenge).

The data fields include:

- `TransactionId`: Unique transaction identifier
- `BatchId`: Unique number assigned to a batch of transactions
- `AccountId`: Unique number identifying the customer
- `SubscriptionId`: Unique number identifying the customer subscription
- `CustomerId`: Unique identifier attached to Account
- `CurrencyCode`: Country currency
- `CountryCode`: Numerical geographical code of country
- `ProviderId`: Source provider of Item bought
- `ProductId`: Item name being bought
- `ProductCategory`: Product categories
- `ChannelId`: Identifies the channel used by the customer
- `Amount`: Value of the transaction
- `Value`: Absolute value of the amount
- `TransactionStartTime`: Transaction start time
- `PricingStrategy`: Category of Xente's pricing structure for merchants
- `FraudResult`: Fraud status of transaction (1 - yes, 0 - no)

## Learning Outcomes

The tasks in this challenge will contribute to the development of the following skills and knowledge:

### Skills:
- Advanced use of scikit-learn
- Feature Engineering
- ML Model building and fine-tuning
- CI/CD deployment of ML models
- Python logging
- Unit testing
- Model management
- MLOps with CML, and MLFlow

### Knowledge:
- Reasoning with business context
- Data exploration
- Predictive analysis
- Machine learning
- Hyperparameter tuning

### Author: Mihret Agegnehu
