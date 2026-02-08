# Linear Regression on E-Commerce Dataset

## 📌 Project Overview

In this project, I applied **Linear Regression** to an e-commerce dataset to get a better understanding of customer behavior and to predict a key target variable: customer spending. The main goal was to explore the data, figure out which features matter most, build a regression model, and evaluate how well it performs using standard error metrics and diagnostic plots.

This project is beginner-friendly and demonstrates the full machine learning workflow, from understanding the data to evaluating the model.

---

## 📂 Dataset

* **Dataset Name:** Linear Regression E-commerce Dataset
* It contains customer-related features that could influence spending behavior.

---

## 🎯 Objective

* Identify the target variable and the input features.
* Explore how different features relate to the target variable.
* Build and assess a Linear Regression model.
* Check if the model assumptions hold using residual analysis.

---

## 🛠️ Steps Performed

### 1️⃣ Understanding the Dataset

* Looked at the dataset structure and the features.
* Identified:

  * Target variable (y)
  * Input features (X)

### 2️⃣ Exploratory Data Analysis (EDA)

* Explored relationships between features and the target variable.
* Used visualizations like `jointplot`, `pairplot`, and `lmplot` to spot trends.
* This helped identify which features could have a significant impact on the target.

### 3️⃣ Data Preparation

* Split the dataset into input variables (X) and target variable (y).
* Performed a train-test split to evaluate the model properly.

### 4️⃣ Model Training

* Trained a Linear Regression model on the training data.

### 5️⃣ Understanding Slope Coefficients

* Examined the model coefficients using `coef_`.

**What are slope coefficients?**

* They indicate how much each input feature contributes to the target variable.
* Higher absolute values mean the feature has more impact.
* They essentially assign weight to the effect of each X on Y.

### 6️⃣ Predictions & Visualization

* Made predictions on the test data.
* Compared actual vs predicted values using a scatter plot.

### 7️⃣ Model Evaluation

* Calculated key metrics:

  * **Mean Absolute Error (MAE):** Average absolute difference between predicted and actual values.
  * **Mean Squared Error (MSE):** Average squared difference between predicted and actual values. Larger errors are penalized more, making it sensitive to outliers.
  * **Root Mean Squared Error (RMSE):** Square root of MSE to bring it back to the original unit of measurement.

* The model performed reasonably well based on these metrics.

### 8️⃣ Residual Analysis & Diagnostics

* Calculated residuals (Actual − Predicted).
* Checked their distribution with `distplot()` and Q-Q plots (`scipy.stats.probplot` with `pylab`).
* Observed that residuals had no major skew and roughly followed a normal distribution.
* This suggests that the model assumptions are largely satisfied.

---

## 📊 Tools & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

## 📈 Key Learnings

* Complete implementation of a Linear Regression project.
* Importance of EDA before building a model.
* How to interpret slope coefficients.
* Understanding MAE, MSE, and RMSE.
* How to check residuals and validate model assumptions.

---

## 🚀 Future Improvements

* Apply feature scaling and regularization (Ridge/Lasso).
* Experiment with non-linear models for comparison.
* Use cross-validation for better evaluation.
* Handle potential outliers in the data.

---

## 🧑‍💻 Author

Yashub Hayat
Data Science Student | Machine Learning Enthusiast


