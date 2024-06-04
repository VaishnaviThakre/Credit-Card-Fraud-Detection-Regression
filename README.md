# Credit Card Fraud Detection Regression

## Overview
This repository contains a project focused on detecting credit card fraud using regression techniques. The goal is to create a model that can accurately predict fraudulent transactions, thereby helping financial institutions minimize losses and protect consumers.

## Problem Statement
The increase in the use of credit cards for transactions has led to a significant rise in credit card fraud, posing a critical challenge for both financial institutions and cardholders. Addressing this issue involves creating a strong machine-learning model capable of effectively differentiating between fraudulent transactions and genuine ones. The model must be capable of predicting fraudulent activities in real-time, thereby ensuring that financial losses are minimized, and consumers' interests are protected. Given the increasing scale and complexity of fraudulent activities, it is essential to utilize advanced technologies in order to create a dependable and effective solution to address this issue.

##	Objective
The main goal is to create a model that can effectively differentiate between legitimate and fraudulent transactions. The success of such a model depends on its ability to make reliable predictions on unseen data and in real-time scenarios. Hence, it is imperative to construct the model with a thorough comprehension of the foundational data and the possible trends in illegitimate transactions. The objective of this research is to create a model that can accurately forecast the legitimacy of transactions and deliver dependable real-time predictions.

## Features
- Data preprocessing and exploration
- Feature engineering
- Model training and evaluation
- Hyperparameter tuning
- Model deployment
- Performance metrics and visualization

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Project Structure](#project-structure)
4. [Data](#data)
5. [Model](#model)
6. [Evaluation](#evaluation)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)


## Installation
To get started, clone the repository and install the required dependencies.

```bash
git clone git@github.com:VaishnaviThakre/Credit-Card-Fraud-Detection-Regression.git
cd Credit-Card-Fraud-Detection-Regression
pip install -r requirements.txt
```

## Usage

1. **Data Preparation:** Download the dataset and place it in the `data/` directory.
2. **Preprocessing:** Run the preprocessing script to clean and prepare the data.

3. **Training:** Train the model using the prepared dataset.

4. **Evaluation:** Evaluate the model's performance on the test dataset.

5. **Prediction:** Use the trained model to make predictions on new data.


## Data
The dataset used in this project is the **Credit Card Fraud Detection** dataset available from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.

### Features:
- `Time`: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- `V1` to `V28`: Result of a PCA transformation to anonymize features.
- `Amount`: Transaction amount.
- `Class`: 1 for fraudulent transactions, 0 otherwise.

## Model
The project employs regression techniques to predict the likelihood of a transaction being fraudulent. The models explored include:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Polynomial Regression

## Evaluation
The model is evaluated using various metrics such as:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

These metrics are calculated and saved in the `results/evaluation_metrics.txt` file.

## Results
Detailed results and performance metrics of the trained models are stored in the `notebooks` directory. Visualizations of the results can be found in the `notebooks` directory.

## Contributing
Contributions are welcome! Please open an issue to discuss what you would like to change or contribute, and submit a pull request.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

