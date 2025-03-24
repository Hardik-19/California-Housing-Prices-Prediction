# California Housing Prices - Machine Learning Project 🏡📊

This project focuses on predicting housing prices in California using machine learning techniques. It leverages data preprocessing, feature engineering, and model optimization to achieve high predictive accuracy.

## Project Overview
**Objective**: Predict median house values based on housing attributes.

**Dataset**: California housing data - https://www.kaggle.com/datasets/camnugent/california-housing-prices?select=housing.csv

**Approach**: Implement various ML models, including Linear Regression, Random Forest, and GridSearchCV for hyperparameter tuning.

## Features & Methodology
- **Data Preprocessing**: Handle missing values, outliers, and categorical encoding.
- **Feature Engineering**: Create new features like bedroom ratio & household density.
- **Data Scaling**: Normalize features using StandardScaler.
- **Model Training**: Train multiple models (Linear Regression, Random Forest).
- **Hyperparameter Tuning**: Optimize model parameters using GridSearchCV.
- **Performance Evaluation**: Evaluate models with R² score.


## Libraries Used
- Scikit-learn (Linear Regression, Random Forest)
- NumPy
- Pandas
- Matplotlib
- Seaborn

## How to Run the Code?
1. **Install required libraries:**
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn
    ```


## Installation
To get started, clone the repository and install the required packages:
```bash
git clone https://github.com/yourusername/california-housing-prices.git
cd california-housing-prices
pip install -r requirements.txt
```

## Usage
Run the main script to preprocess the data, train the models, and evaluate their performance:
```bash
python main.py
```
