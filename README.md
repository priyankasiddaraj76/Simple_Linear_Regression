# README — Own Simple Linear Regression

# Own Implementation of Simple Linear Regression

A Machine Learning project where **Simple Linear Regression** is implemented completely from scratch using Python without relying on Scikit-learn’s built-in regression model.

This project demonstrates the mathematical intuition behind linear regression by manually calculating the slope and intercept using formulas.

---

## Overview

The project builds a custom Linear Regression class named `myLR` and trains it on a placement dataset containing:

* `CGPA` → Input feature
* `Package` → Target variable

The implementation:

* Calculates slope (`m`) manually
* Calculates intercept (`b`) manually
* Predicts output using the regression equation
* Mimics how Scikit-learn internally works

---

## Concepts Covered

### 1. Simple Linear Regression

A supervised learning algorithm used to predict continuous values.

Regression Equation:

```text
y = mx + b
```

Where:

* `m` = slope
* `b` = intercept
* `x` = input feature
* `y` = predicted output

---

### 2. Gradient-Free Mathematical Implementation

Instead of using optimization libraries, the project directly computes:

* Mean values
* Covariance
* Variance
* Best fit line

---

### 3. Train-Test Split

Splitting the dataset into:

* Training data
* Testing data

using Scikit-learn.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

---

## Formula Used

### Slope

```text
m = Σ[(x - x̄)(y - ȳ)] / Σ[(x - x̄)^2]
```

### Intercept

```text
b = ȳ - m(x̄)
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/own-simple-linear-regression.git
cd own-simple-linear-regression
```

Install dependencies:

```bash
pip install numpy pandas scikit-learn
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```bash
Own_Simple_Linear_Regression.ipynb
```

---

## Learning Outcomes

By completing this project, you will understand:

* How Linear Regression works internally
* Mathematical derivation of slope and intercept
* How prediction equations are formed
* How machine learning models are implemented from scratch
* Difference between manual implementation and Scikit-learn

---

## Future Improvements

Possible enhancements:

* Add visualization of regression line
* Implement Gradient Descent version
* Add evaluation metrics (MAE, MSE, RMSE)
* Extend to Multiple Linear Regression

---

## License

This project is open-source and available under the MIT License.

# README — Simple Linear Regression Using Scikit-learn

# Simple Linear Regression

A beginner-friendly Machine Learning project that demonstrates how to implement **Simple Linear Regression** using Scikit-learn.

The project predicts placement packages based on student CGPA and visualizes the regression relationship using Matplotlib.

---

## Overview

This project:

* Loads a placement dataset
* Visualizes linear relationships
* Trains a Linear Regression model
* Predicts salary/package values
* Plots the best fit regression line

The notebook is ideal for understanding the basics of supervised learning and regression.

---

## Dataset

The dataset contains:

* `cgpa` → Student CGPA
* `package` → Placement package in LPA

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Machine Learning Concepts Covered

### 1. Supervised Learning

Learning from labeled training data.

### 2. Linear Regression

A regression algorithm used for predicting continuous values.

Regression equation:

```text
y = mx + b
```

---

### 3. Data Visualization

Using scatter plots to analyze relationships between variables.

### 4. Train-Test Split

Separating data into training and testing sets.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/simple-linear-regression.git
cd simple-linear-regression
```

Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```bash
Simple_linear_regression.ipynb
```

---

## Learning Outcomes

After completing this project, you will understand:

* Basics of Linear Regression
* Data preprocessing
* Training ML models using Scikit-learn
* Visualizing regression models
* Making predictions using trained models

---

## Future Improvements

Possible enhancements:

* Add evaluation metrics
* Compare multiple regression models
* Implement polynomial regression
* Deploy model using Flask or Streamlit

---

## License

This project is open-source and available under the MIT License.
