# Phishing Classifier using Machine Learning

## Overview
The Phishing Classifier project aims to predict whether a given URL is a legitimate website or a phishing attempt. The dataset includes various features extracted from URLs, such as domain characteristics, path details, and other relevant attributes. The goal is to build an accurate binary classification model that identifies potential phishing URLs.

## Dataset Description
The dataset contains the following features:

1. **NumDots**: Quantitative, representing the number of dots (periods) in the URL.
2. **SubdomainLevel**: Quantitative, indicating the level of subdomains in the URL.
3. **PathLevel**: Quantitative, indicating the depth of the URL path.
4. **UrlLength**: Quantitative, measuring the length of the URL.
5. **NumDash**: Quantitative, counting the number of dashes in the URL.
6. **NumDashInHostname**: Quantitative, counting dashes specifically in the hostname.
7. **AtSymbol**: Binary, indicating the presence of the "@" symbol in the URL.
8. **TildeSymbol**: Binary, indicating the presence of the "~" symbol in the URL.
9. ... (continue with other features)
10. **CLASS_LABEL**: Binary, representing whether the URL is a phishing site (1) or not (0).

## Project Structure
1. `data/`: Contains the phishing dataset (e.g., `phishing_data.csv`).
2. `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model building.
3. `models/`: Trained classification models (e.g., `logistic_regression_model.pkl`).
4. `src/`: Python scripts for data preprocessing, model training, and evaluation.
5. `README.md`: This file, providing an overview of the project.

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python packages (e.g., `numpy`, `pandas`, `scikit-learn`).
3. Explore the data using the Jupyter notebooks in the `notebooks/` directory.
4. Train a classification model (e.g., logistic regression, random forest) to predict phishing URLs.
5. Evaluate the model's performance (accuracy, precision, recall, F1-score).

## Usage
1. Load the phishing dataset (`phishing_data.csv`) using the provided Python script.
2. Preprocess the data (handle missing values, encode categorical features, etc.).
3. Train a classification model using the processed data.
4. Evaluate the model's performance on a validation set.
5. Save the trained model for future predictions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
