# Credit Card Fraud Detection

This project implements a machine learning pipeline for detecting fraudulent credit card transactions. It includes data preprocessing, feature scaling, handling class imbalance, training multiple classifiers, and evaluating model performance.

## Features

- **Data Preprocessing**: Outlier removal, class balancing using SMOTE, and feature scaling.
- **Model Training**: Logistic Regression classifier with performance evaluation.
- **Visualization**: Class distribution, correlation heatmaps, and confusion matrices.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.6+
- `pip` (Python package installer)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/riyachiraniya/credit-card-fraud-detection.git
    cd credit-card-fraud-detection
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Place your dataset (`creditcard.csv`) in the specified directory or update the file path in the script.

2. Run the script:

    ```bash
    python fraud_detection.py
    ```

3. The script will perform the following actions:
   - Load and preprocess the dataset.
   - Handle class imbalance using SMOTE.
   - Train a Logistic Regression model.
   - Output performance metrics and visualizations.

### Output

- **Class Distribution Plot**: Visualizes the distribution of fraudulent vs. non-fraudulent transactions.
- **Confusion Matrix**: Shows the performance of the Logistic Regression model.
- **Classification Report**: Provides detailed performance metrics for the Logistic Regression model.

## Data

The dataset used is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets?search=credit+card+fraud) from Kaggle. This dataset includes various features of transactions and a binary label indicating fraudulent activity.

## Disclaimer

The results obtained are based on the provided dataset and the specific models used in this script. It's important to validate these models with additional data and possibly refine them for practical applications.

## Acknowledgments

- [Keras](https://keras.io/)
- [scikit-learn](https://scikit-learn.org/)
- [imbalanced-learn](https://imbalanced-learn.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

## Contact

For questions or comments, please open an issue on GitHub.
