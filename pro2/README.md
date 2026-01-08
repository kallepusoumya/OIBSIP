# Credit Card Fraud Detection

This project demonstrates fraud detection in financial transactions using machine learning techniques. It leverages advanced analytics, anomaly detection, pattern recognition, and real-time monitoring to distinguish between legitimate and fraudulent activities.

## Overview

Fraud detection is crucial in the financial sector to prevent deceptive activities. This implementation uses the Kaggle Credit Card Fraud Detection dataset to build and evaluate models that can identify fraudulent transactions.

## Features

- **Data Exploration**: Initial analysis of the dataset including statistics and class distribution
- **Data Preprocessing**: Feature scaling and train-test split with stratification
- **Anomaly Detection**: Isolation Forest algorithm for unsupervised anomaly detection
- **Pattern Recognition**: Random Forest classifier for supervised fraud classification
- **Real-Time Simulation**: Simulated real-time monitoring of transactions
- **Model Evaluation**: Comprehensive evaluation with metrics, confusion matrix, and ROC curves

## Dataset

The project uses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle, which contains transactions made by credit cards in September 2013 by European cardholders. The dataset includes:

- 284,807 transactions
- 31 features (28 anonymized features + Time + Amount)
- Highly imbalanced classes (0.172% fraud rate)

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd pro2
   ```

2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook fraud_detection.ipynb
   ```

2. Run all cells in sequence to:
   - Load and explore the data
   - Preprocess the features
   - Train anomaly detection and classification models
   - Evaluate model performance
   - Simulate real-time fraud monitoring

## Models

### Anomaly Detection
- **Algorithm**: Isolation Forest
- **Training**: Only on legitimate transactions
- **Purpose**: Identify unusual patterns without labeled fraud data

### Pattern Recognition
- **Algorithm**: Random Forest Classifier
- **Training**: Supervised learning on labeled data
- **Purpose**: Classify transactions as fraudulent or legitimate

## Results

The Random Forest model achieves:
- **Precision**: 94% for fraud detection
- **Recall**: 82% for fraud detection
- **ROC-AUC**: 0.97

## Real-Time Monitoring

The simulation processes transactions sequentially, combining both anomaly detection and classification models to flag potential fraud in real-time scenarios.

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.