# House Price Prediction using Machine Learning

## Overview

This project focuses on predicting residential house prices using the Ames Housing Dataset. The workflow includes data exploration, preprocessing, feature engineering, handling missing values, encoding categorical features, and training a Linear Regression model for price prediction.

The objective is to understand how different housing attributes influence property prices and build a machine learning model capable of estimating house values from historical housing data.

---

## Dataset

The project uses the Ames Housing Dataset, which contains detailed information about residential properties, including:

* Property size
* Construction year
* Overall quality and condition
* Number of rooms and bathrooms
* Garage information
* Neighborhood characteristics
* Sale price

Target Variable:

* `SalePrice`

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Dataset inspection
* Distribution analysis of house prices
* Log transformation of target variable
* Visualization of important housing features
* Correlation analysis

### 2. Data Preprocessing

* Handling missing values
* Converting categorical numerical features to string format
* Feature scaling
* Data cleaning

### 3. Feature Engineering

* Creation of Total Square Footage feature
* Removal of redundant features
* One-Hot Encoding of categorical variables

### 4. Model Training

* Train-Test Split
* Linear Regression Model

### 5. Model Evaluation

Performance was evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Visualizations

The project includes several visual analyses such as:

* House Price Distribution
* Log-Transformed Price Distribution
* Missing Value Analysis
* Correlation Heatmap
* Zoning Classification Analysis
* Construction Age vs Price Analysis
* Actual vs Predicted House Price Comparison

---

## Repository Structure

```text
House-Price-Prediction/
│
├── HousePricePrediction.ipynb
├── README.md
├── requirements.txt
└── train.csv
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
HousePricePrediction.ipynb
```

---

## Results

The Linear Regression model successfully captured the relationship between housing features and sale prices. Through feature engineering, preprocessing, and encoding techniques, the model demonstrated effective predictive performance on unseen test data.

---

## Future Improvements

* Hyperparameter tuning
* Advanced regression models
* Ensemble methods
* Model deployment using Streamlit or Flask
* Feature importance analysis

---

## Author

Sifat Bhatia

B.Tech Computer Science Engineering

Interested in Machine Learning, Artificial Intelligence, Quantum Machine Learning, and AI-Powered Cybersecurity.
