# Credit Card Fraud Detection

## SE4050 Deep Learning Assignment

This project focuses on detecting fraudulent credit card transactions using Deep Learning.

## Dataset

The project uses the Credit Card Fraud Detection dataset obtained from Kaggle.

The dataset contains transaction features including:

- Time
- V1–V28
- Amount
- Class

Where:

- Class 0 = Legitimate transaction
- Class 1 = Fraudulent transaction

## Data Preprocessing

The initial dataset contains 284,807 transactions.

During the initial data cleaning stage:

- Missing values were checked.
- Duplicate rows were identified.
- 1,081 duplicate rows were removed.
- The cleaned dataset contains 283,726 transactions.
- No missing values remain.

## Deep Learning Models

The project will implement and compare:

1. Multi-Layer Perceptron (MLP)
2. 1D Convolutional Neural Network (1D CNN)
3. Long Short-Term Memory (LSTM)
4. Gated Recurrent Unit (GRU)

## Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── data/
├── notebooks/
├── src/
├── results/
├── models/
├── README.md
├── requirements.txt
└── .gitignore