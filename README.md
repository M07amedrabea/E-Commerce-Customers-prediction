# E-Commerce Customers - ML - Regression Project

## Overview

This project applies multiple machine learning regression models to analyze and predict customer behavior based on e-commerce data. The models used include:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Neighbors Regressor
- Support Vector Regressor (SVR)

## Dataset

The dataset contains numerical and categorical features related to e-commerce customers. The goal is to predict customer spending based on available features.

## Libraries Used

The following Python libraries are used in the project:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

## Steps in the Project

1. **Importing Libraries**
2. **Loading the Dataset**
3. **Exploring and Visualizing Data**
4. **Feature Selection and Preprocessing**
5. **Splitting Data into Training and Testing Sets**
6. **Training and Evaluating Machine Learning Models**
7. **Comparing Model Performance**
8. **Reverse Regression (Predicting Features from Target Values)**

## How to Run the Project

1. Install the required dependencies using:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Open the Jupyter Notebook (`CODE.ipynb`).
3. Run the notebook cells sequentially to load data, preprocess, train models, and evaluate results.

## Results

The models are evaluated based on metrics such as:

- Mean Squared Error (MSE)
- R-squared Score (R²)
- Mean Absolute Error (MAE)

## Future Improvements

- Hyperparameter tuning for better model performance.
- Feature engineering to enhance prediction accuracy.
- Deployment of the model using Flask or FastAPI for real-world usage.

