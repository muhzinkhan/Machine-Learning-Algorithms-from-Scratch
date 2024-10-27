# Multivariate Linear Regression using Gradient Descent

This project demonstrates the implementation of a multivariate linear regression model from scratch in Python, using gradient descent for optimization. The loss function is defined as the Sum of Squared Errors (SSE). This project does not rely on external libraries like SciPy or scikit-learn, emphasizing a full manual implementation to understand the underlying mathematics.

## Project Structure

All code for this project can be found in the Jupyter notebook: [Linear-Regression.ipynb](Linear-Regression.ipynb). The notebook includes data preparation, model implementation, training process, and evaluation metrics.

## Getting Started

1. Clone this repository to your local machine.
2. Open the `Linear-Regression.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Follow along with the code and comments to see the multivariate linear regression model built and trained from scratch.

## Assumptions of Multivariate Linear Regression

This linear regression model assumes the following:

1. **Linearity**: The relationship between the independent variables (features) and the dependent variable (target) is linear.
2. **Independence**: Observations are independent of each other.
3. **Homoscedasticity**: The variance of errors is constant across all levels of the independent variables.
4. **No Perfect Multicollinearity**: No independent variable is a perfect linear function of any other independent variables.
5. **Normality of Errors**: The residuals (errors) are normally distributed (especially important for small sample sizes).

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Numpy (for basic array manipulation)

## Running the Model

Open `Linear-Regression.ipynb` and execute the cells in sequence. This notebook includes:
- Data preparation
- Model training with gradient descent
- Evaluation of model performance

