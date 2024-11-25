---
title: "Credit Card Fraud Detection"
_build:
  render: always
  list: always
  publishResources: true
---

# Credit Card Fraud Detection

This project focuses on detecting credit card fraud using various machine learning techniques. The primary challenge in this domain is the substantial imbalance between fraudulent and non-fraudulent transactions. This project aims to address this issue by leveraging different machine learning models and techniques to improve fraud detection accuracy and computational efficiency.

## Project Overview

Credit card fraud detection is a critical task in the financial industry due to the significant financial losses and emotional distress it causes. The primary challenge in this domain is the substantial imbalance between fraudulent and non-fraudulent transactions. This project aims to address this issue by leveraging different machine learning models and techniques to improve fraud detection accuracy and computational efficiency.

## Methodology

### Dataset

The dataset used in this project is the Credit Card Fraud Detection dataset, which includes transactions made by European cardholders over two days. The dataset contains 284,807 transactions, with only 492 labeled as fraudulent, highlighting the class imbalance.

### Features

- **V1 to V28**: Principal Component Analysis (PCA) transformed features.
- **Time**: Time elapsed between each transaction and the first transaction in the dataset.
- **Amount**: Transaction amount.

### Addressing Class Imbalance

Two techniques were employed to handle the class imbalance:
- **Under-sampling**: Balancing the dataset by randomly selecting a subset of non-fraudulent transactions.
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Generating synthetic samples to balance the dataset.

### Machine Learning Models

The following machine learning models were evaluated:
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Random Forest (RF)**
- **Bagging**
- **Boosting**
- **Logistic Regression (LR)**

### Ensemble Model

An ensemble model combining SVM, KNN, RF, Bagging, and Boosting within a voting framework was proposed. This model aims to leverage the strengths of individual classifiers to enhance overall performance.

## Results

The performance of the models was evaluated using various metrics, including precision, recall, F1-score, ROC, and accuracy. The ensemble model demonstrated superior performance in terms of reducing false positives and false negatives, which are critical in fraud detection.

### Key Findings

- The ensemble model effectively addressed the class imbalance and improved detection accuracy.
- Computational efficiency was analyzed, revealing trade-offs between training and testing times among different models.
- The ensemble approach provided a balanced solution, offering both high accuracy and computational efficiency.

## Future Work

Future research should focus on:
- Enhancing model efficiency to enable real-time fraud detection.
- Integrating deep learning models such as CNNs and RNNs with traditional machine learning methods.
- Exploring dynamic data sampling strategies to adapt to changes in data distribution.
- Investigating methods to improve model resilience against novel or adversarial attacks.
- Assessing model scalability to handle larger datasets and increased computational demands.

## Conclusion

This project highlights the effectiveness of using ensemble learning techniques for credit card fraud detection, addressing the challenges of data imbalance and computational efficiency. The proposed model provides a robust solution for detecting fraudulent transactions, with potential for further improvements through advanced techniques and strategies.

## Contributors

- Daniele Laganà
- Gianluigi Palmisano

## Supervisor

- Prof. Edie Miglio

## Acknowledgements

This project was completed as part of the Numerical Analysis for Machine Learning course for the academic year 2023-2024.

## Keywords

Credit card fraud detection, machine learning, ensemble learning, data imbalance, SMOTE, computational efficiency.

## GitHub Repository

For more details, visit the [GitHub repository](https://github.com/danielelagana/credit-card-fraud-detection-ML).

