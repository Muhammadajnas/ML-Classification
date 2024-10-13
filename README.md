# Machine Learning-Based Ransomware Classification of Bitcoin Transactions

## Overview
This project introduces a Ransomware Detection System (RDS) that leverages machine learning to classify ransomware transactions within the Bitcoin network. Using the **BitcoinHeist dataset**, the study applies ensemble learning models to identify and categorize ransomware transactions. The framework integrates Decision Trees, Random Forest, XGBoost, and stacking techniques to improve classification accuracy, along with feature engineering and hyperparameter optimization.

## Key Features
- **BitcoinHeist Dataset**: A dataset containing Bitcoin transactions associated with 28 ransomware families and legitimate transactions.
- **Supervised Learning**: Classifies transactions using Decision Tree, Random Forest, and XGBoost models.
- **Stacking Ensemble**: Combines the outputs of the base models using a Multilayer Perceptron (MLP) to improve detection accuracy.
- **Feature Engineering**: New features are derived using arithmetic operations and clustering techniques for better detection accuracy.
- **Hyperparameter Optimization**: Implements **Optuna** for tuning models to improve performance.

## Dataset
The dataset used is the **BitcoinHeist** dataset, which consists of Bitcoin transactions classified as ransomware-related or legitimate. It includes attributes such as:
- Address
- Year, Day
- Transaction count
- Income (Satoshi)
- Ransomware family labels

## Methodology
1. **Data Preprocessing**: Includes label encoding, outlier removal, power transformation, and standardization.
2. **Data Balancing**: Techniques such as **SMOTE** (Synthetic Minority Over-sampling Technique) and random undersampling are used to handle class imbalance.
3. **Feature Selection**: The most important features are selected using Gradient Boosting Classifier, optimized through **Optuna**.
4. **Machine Learning Models**: Decision Tree, Random Forest, XGBoost, and a stacking ensemble model are used to classify ransomware transactions.
5. **Performance Evaluation**: Models are evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/muhammadajnas/ML-Classification.git

## Results
The RDS framework achieves:

**Accuracy**: Up to 96.16% using a stacking ensemble model.
**Precision and Recall**: High detection rates for both known ransomware and legitimate transactions.
**Hyperparameter Optimization**: Results in improved performance compared to untuned models.

## Future Work
Implement the detection framework in real-time Bitcoin transaction monitoring systems.
Extend to other cryptocurrencies and blockchain technologies.
Explore integration of external threat intelligence sources for enhanced detection.

## Contact
For more information, contact:

## Muhammad Ajnas
### muhammadajnas2001@gmail.com
