# Car Price Prediction with Linear Regression

## 1. Project Overview

This project implements a Linear Regression and Lasso model to predict the price of cars based on various features like engine size, mileage, year, brand, and more. The goal is to build a model that can accurately predict the price of a car based on its specifications and condition.


## 2. Dataset Source

https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

## 3. Features
- **Data Preprocessing**: Data cleaning, feature engineering, handling missing values, and splitting into training and testing sets.
- **Model Training**: Training a Linear Regression and Lasso model using scikit-learn.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).
- **Visualization**: Visualization of feature relationships and residual plots to assess the model's accuracy.



## 4. Project Structure
    ├── car data.csv                # Dataset file 
    ├── car_price_prediction.ipynb  # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/car_price.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook car_price_prediction.ipynb
```
## 6. Usage

Open the car_price_prediction.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the 'car data.csv' and perform necessary preprocessing like handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Train a Linear Regression and Lasso model to predict car prices based on features like horsepower, mileage, and year.
- **Model Evaluation**:  Evaluate the model using metrics such as MAE, RMSE, and R² to understand how well the model predicts car prices.
- **Visualization**:  Visualize the relationships between different features and car price using scatter plots and analyze residuals to validate the model's accuracy.


## 7. Results in Test

- Linear Regression

| Metric    |  Value |
|-----------|--------|
| Mean Absolute Error  |  1.26   |
| Root Mean Squared Error	 |  1.71   |
| R-squared (R²)    | 0.84  |

- Lasso

| Metric    |  Value |
|-----------|--------|
| Mean Absolute Error  |  1.28   |
| Root Mean Squared Error	 |  2.0   |
| R-squared (R²)    | 0.84  |



## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







