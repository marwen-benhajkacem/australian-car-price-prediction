# Australian Car Price Prediction

## Overview

This project focuses on predicting Australian vehicle prices using Machine Learning regression algorithms.

It explores the complete data analysis and modeling workflow, from data cleaning and exploratory data analysis to feature engineering, model training, and hyperparameter optimization.

The main objective is to identify the regression model that provides the best predictive performance based on vehicle characteristics.

## Project Objectives

- Understand and analyze vehicle pricing data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Engineer relevant features.
- Apply categorical encoding and normalization.
- Train and compare regression models.
- Optimize model hyperparameters.

## Dataset

The dataset contains information about Australian vehicles, including:

- Brand and model
- Manufacturing year
- Vehicle condition
- Transmission
- Engine specifications
- Fuel type
- Mileage
- Body type
- Vehicle price

**Target variable:** `Price`

The original dataset is not included in this repository pending confirmation of its redistribution license.

To reproduce the project, obtain the dataset from its original source and place it at:

`data/raw/Australian_Vehicle_Prices.csv`

## Machine Learning Workflow

### 1. Data Cleaning
- Missing value analysis and treatment.
- Duplicate removal.
- Data type conversion.
- Irrelevant feature removal.

### 2. Exploratory Data Analysis
- Price distribution analysis.
- Categorical feature visualization.
- Correlation analysis.
- Relationship exploration between vehicle characteristics and prices.

### 3. Feature Engineering
- Vehicle age calculation.
- Feature transformation.
- Categorical encoding.
- Numerical normalization.

### 4. Regression Models

The project explores:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 5. Hyperparameter Optimization

GridSearchCV is used to explore model configurations and improve predictive performance.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook

## Repository Structure

```text
australian-car-price-prediction/
│
├── data/
│   └── raw/
│
├── notebooks/
│   └── australian_car_price_prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

### 1. Clone the repository

```bash
git clone git@github.com:YOUR_USERNAME/australian-car-price-prediction.git
cd australian-car-price-prediction
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add the dataset

Place the original CSV file in:

```text
data/raw/Australian_Vehicle_Prices.csv
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook in the `notebooks/` directory.

## Future Improvements

- Improve preprocessing with Scikit-learn Pipelines.
- Prevent data leakage.
- Apply more appropriate categorical encoding techniques.
- Implement cross-validation.
- Evaluate models using additional regression metrics.
- Explore advanced regression algorithms.
- Develop a reusable prediction pipeline.

## Author

**Marouen Ben Haj Kacem**

Machine Learning & Data Science

[GitHub Profile](https://github.com/marwen-benhajkacem)

---

*This project is intended for educational and experimental purposes.*
