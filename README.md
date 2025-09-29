# LINEAR-REGRESSION-FROM-SCRATCH

## Abstract

This notebook presents the implementation of **Simple Linear Regression** from scratch using Python, applied to the **Years of Experience vs Salary dataset**. The goal is to predict salaries based on years of experience by deriving the regression line using **Ordinary Least Squares (OLS)** and comparing results against scikit-learn’s implementation.

---

## Objective

* To implement linear regression using mathematical foundations without relying solely on pre-built ML libraries.
* To validate the custom implementation against **scikit-learn’s LinearRegression** model.
* To visualize the regression line and evaluate prediction accuracy.

---

## Dataset

* **Dataset Used:** `Salary_Data.csv`
* **Features:**

  * Independent Variable (X): Years of Experience
  * Dependent Variable (y): Salary
* **Type:** Real-world dataset commonly used for linear regression demonstrations.

---

## Methodology

1. **Data Loading & Preprocessing**

   * Import data with `pandas`.
   * Explore dataset structure and statistics.

2. **Scratch Implementation**

   * Define cost function (Mean Squared Error).
   * Implement gradient descent to optimize slope and intercept.
   * Build prediction function using optimized parameters.

3. **Model Evaluation**

   * Visualize regression line vs data points (`matplotlib`, `seaborn`).
   * Compare custom model outputs with scikit-learn’s `LinearRegression`.

---

## Results

* The **scratch-built regression line** closely aligns with scikit-learn’s predictions.
* Demonstrates the feasibility of deriving regression models from first principles.
* Strengthens conceptual understanding of **linear regression mechanics**.

---

## Technologies Used

* **Programming Language:** Python
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
* **Environment:** Jupyter Notebook

---

## References

1. James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). *An Introduction to Statistical Learning*. Springer.
2. Scikit-learn Documentation – Linear Models: [https://scikit-learn.org/stable/modules/linear_model.html](https://scikit-learn.org/stable/modules/linear_model.html)
3. Dataset Source: [Kaggle – Salary Data](https://www.kaggle.com/datasets)

---

## Future Work

* Extend to **Multiple Linear Regression**.
* Apply **Polynomial Regression** for non-linear relationships.
* Experiment with **Ridge and Lasso regularization**.
