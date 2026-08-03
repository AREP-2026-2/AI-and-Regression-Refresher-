# Stellar Luminosity Regression

This project explores how a regression model learns from data by implementing linear and polynomial regression from first principles. It uses a small instructional dataset relating stellar mass and luminosity, trains both models with vectorized NumPy operations, and compares their behavior inside and outside the observed data range.

## MADE BY:
- Sebastian Albarracin Silva 

## Requirements

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## How to Run

Install the required libraries:

```bash
python -m pip install numpy matplotlib
```

Then open `stellar_luminosity_hands_on.ipynb` in Jupyter Notebook, JupyterLab, VS Code, or GitHub, and run all cells from top to bottom.

## Main Result

The polynomial model represents the observed nonlinear relationship better than the linear model within the training range. However, lower training error does not prove scientific validity, especially for extrapolated predictions far outside the available evidence.
