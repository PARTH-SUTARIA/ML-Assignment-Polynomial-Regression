# ML Assignment 1 - Polynomial Regression

Roll number: **BT2024028**

Polynomial regression models for the two assigned problems (var1 and var2). The degree, the features and the regularization (none, ridge or lasso) are chosen with 10-fold cross validation using MSE and R2, and the best model is used to predict on the test set.

## Links

- GitHub: https://github.com/PARTH-SUTARIA/ML-Assignment-Polynomial-Regression
- Colab (Var1): https://colab.research.google.com/drive/18dNQw658h0kiuL-LHYj6j6jANrFhd9qA?usp=sharing
- Colab (Var2): https://colab.research.google.com/drive/19Q_mxwSLCXlwGFjeX7EkbOZ6_g03l6AX?usp=sharing

## How to run

1. Install the requirements:
   ```
   pip install numpy pandas matplotlib scikit-learn
   ```
2. Keep each notebook in the same folder as its train and test CSV files.
3. Open `BT2024028_Var1.ipynb` or `BT2024028_Var2.ipynb` and run all cells.

Each notebook writes its predictions to `BT2024028_pred_var1.csv` or `BT2024028_pred_var2.csv` in the same folder.
