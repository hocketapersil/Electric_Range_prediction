# Regression Project

## Overview
This project aims to predict the electric range of vehicles using various regression models. The analysis includes data preprocessing, feature engineering, model training, evaluation, and visualization of results.

## Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Files
- `RegressionProject.ipynb`: The main Jupyter Notebook containing the entire analysis and model training process.

## Installation
1. Clone the repository or download the `RegressionProject.ipynb` file.
2. Ensure you have Python and Jupyter Notebook installed on your system.
3. Install the required libraries using the following command:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
4. Open the Jupyter Notebook:
    ```sh
    jupyter notebook RegressionProject.ipynb
    ```

## Data Preprocessing
1. Load the dataset into a pandas DataFrame.
2. Handle missing values through imputation or removal.
3. Perform feature engineering to create new features.
4. Encode categorical variables using one-hot encoding or label encoding.
5. Scale and normalize the features.

## Model Training and Evaluation
1. Split the dataset into training and testing sets.
2. Train multiple regression models including Linear Regression, Decision Tree Regression, and Random Forest Regression.
3. Evaluate the models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).
4. Perform cross-validation to ensure model stability and reliability.

## Results
- The Random Forest Regression model was found to be the most effective, with the best performance metrics:
  - MSE: [0.03759537919941116]
  - R²: [0.992712415556006] = 99.3% accurate.

## Visualizations
1. Feature importance plot for the Random Forest model.
2. Scatter plot of actual vs predicted values.
3. Residuals vs predicted values plot.

## Conclusion
The analysis successfully demonstrates the use of regression models to predict electric vehicle range. The Random Forest model provided the most accurate predictions. Future work could include further hyperparameter tuning and exploration of additional features.

## Usage
1. Follow the instructions in the Jupyter Notebook to replicate the analysis.
2. Modify the code as needed to apply to your own dataset or to try different regression models.

## License
This project is licensed under the MIT License.
