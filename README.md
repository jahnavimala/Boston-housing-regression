# Boston Housing Price Prediction
A machine learning project implementing regression analysis to predict real estate prices using the Boston Housing dataset.

## Project Objective
The goal of this project is to predict the median value of owner-occupied homes in Boston using various neighborhood and property attributes. This is a **supervised learning** task using **Regression**.

## Dataset
The dataset is sourced from the [Kaggle Boston CSV](https://www.kaggle.com/puxama/bostoncsv). It includes 506 instances and 14 attributes, such as:
* **CRIM**: Per capita crime rate by town.
* **RM**: Average number of rooms per dwelling.
* **LSTAT**: Percentage of lower status of the population.
* **MEDV**: Median value of owner-occupied homes (Target Variable).

## Analysis Highlights
- **Correlation Analysis**: Identified that `RM` has the highest positive correlation with price.
- **Model Used**: Linear Regression / Random Forest Regressor.
- **Performance**: Achieved an R-squared score of [Insert Your Score, e.g., 0.74].

## How to Run
1. Clone the repo: `git clone https://github.com/yourusername/Boston-Housing-Price-Predictor.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook notebooks/analysis.ipynb`
