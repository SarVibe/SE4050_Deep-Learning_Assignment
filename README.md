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
├── notebooks/
│   │
│   ├── 01_preprocessing/
│   │   └── Credit_Card_Fraud_Detection.ipynb
│   │
│   ├── 02_MLP/
│   │   └── MLP_model.ipynb
│   │
│   ├── 03_CNN/
│   │   └── CNN_model.ipynb
│   │
│   ├── 04_LSTM/
│   │   └── LSTM_model.ipynb
│   │
│   └── 05_GRU/
│       └── GRU_model.ipynb
│
├── src/
│   │
│   ├── preprocessing.py
│   ├── evaluation.py
│   └── utils.py
│
├── results/
│   │
│   ├── figures/
│   │   │
│   │   ├── MLP/
│   │   │   ├── training_history.png
│   │   │   ├── confusion_matrix.png
│   │   │   └── roc_curve.png
│   │   │
│   │   ├── CNN/
│   │   │   ├── training_history.png
│   │   │   ├── confusion_matrix.png
│   │   │   └── roc_curve.png
│   │   │
│   │   ├── LSTM/
│   │   │   ├── training_history.png
│   │   │   ├── confusion_matrix.png
│   │   │   └── roc_curve.png
│   │   │
│   │   └── GRU/
│   │       ├── training_history.png
│   │       ├── confusion_matrix.png
│   │       └── roc_curve.png
│   │
│   └── tables/
│       ├── MLP_results.csv
│       ├── CNN_results.csv
│       ├── LSTM_results.csv
│       ├── GRU_results.csv
│       └── model_comparison.csv
│
├── models/
│   ├── MLP/
│   │   └── MLP_best_model.keras
│   │
│   ├── CNN/
│   │   └── CNN_best_model.keras
│   │
│   ├── LSTM/
│   │   └── LSTM_best_model.keras
│   │
│   └── GRU/
│       └── GRU_best_model.keras
│
├── README.md
└── .gitignore