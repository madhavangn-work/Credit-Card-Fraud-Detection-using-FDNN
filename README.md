# Credit Card Fraud Detection using Feedforward Deep Neural Network (FDNN)

This project aims to detect fraudulent credit card transactions using a Feedforward Deep Neural Network (FDNN). The dataset used for this project is the well-known Credit Card Fraud Detection dataset, which contains transactions made by credit cards in September 2013 by European cardholders.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Credit card fraud is a significant issue in the financial industry, and early detection is crucial to prevent substantial financial losses. This project implements a Feedforward Deep Neural Network (FDNN) to classify transactions as fraudulent or legitimate based on various features.

## Dataset

The dataset used in this project is sourced from Kaggle [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud] and contains the following features:
- `Time`: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- `V1, V2, ..., V28`: Principal components obtained using PCA to protect user identities and sensitive features.
- `Amount`: Transaction amount.
- `Class`: Class label (0 for legitimate, 1 for fraudulent).

You can install these dependencies using pip:

```
pip install pandas numpy matplotlib scikit-learn tensorflow keras
```

## Usage

1. Clone this repository:
```
git clone https://github.com/yourusername/credit-card-fraud-detection.git
```

2. Navigate to the project directory:
```
cd credit-card-fraud-detection
```

3. Place the `creditcard.csv` dataset in the project directory.

4. Open the Jupyter Notebook `FDNN.ipynb`

5. Run the notebook cells to train the model and evaluate its performance.

## Results

The performance of the model is evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

These metrics provide a comprehensive evaluation of the model's ability to detect fraudulent transactions accurately.

## Contributing

Contributions to this project are welcome. You can contribute by:

- Reporting bugs
- Suggesting new features
- Writing or improving - documentation
- Submitting pull requests

Please ensure that your contributions align with the project's coding style and standards.