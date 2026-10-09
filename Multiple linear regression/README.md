# Multiple Linear Regression (MLR)

## 📌 Overview

Multiple Linear Regression is a **Supervised Machine Learning algorithm** used to predict a continuous numerical value using two or more independent variables (features).

Unlike Simple Linear Regression, which uses only one input feature, Multiple Linear Regression uses multiple features to predict the target variable.

**Example:** Predicting a student's marks using study hours, attendance, and previous exam marks.

---

## 🎯 Objective

* Understand Multiple Linear Regression.
* Learn how multiple input features affect a target variable.
* Train a regression model using Python and Scikit-learn.
* Evaluate model performance using regression metrics.
* Predict numerical values using unseen data.

---

## 🧮 Mathematical Formula

The general equation of Multiple Linear Regression is:

$$
\hat{y}=b_0+b_1x_1+b_2x_2+\cdots+b_nx_n
$$

Where:

* **ŷ** — Predicted output
* **b₀** — Intercept
* **b₁, b₂, ..., bₙ** — Coefficients of the features
* **x₁, x₂, ..., xₙ** — Independent variables (features)
* **n** — Number of input features

### Example

Suppose we predict student marks using three features:

$$
\hat{y}=10+5x_1+0.2x_2+0.5x_3
$$

Where:

* \(x_1\) = Hours studied
* \(x_2\) = Attendance percentage
* \(x_3\) = Previous exam marks

If a student studies for 6 hours, has 80% attendance, and scored 70 marks previously:

$$
\hat{y}=10+5(6)+0.2(80)+0.5(70)
$$

$$
\hat{y}=91
$$

**Predicted marks = 91**

*Note: The coefficients in this example are illustrative.*

---

## 🔄 Workflow of Multiple Linear Regression

```text
             Start
               |
               v
         Collect Dataset
               |
               v
      Understand and Clean Data
               |
               v
       Separate Features (X)
         and Target (y)
               |
               v
        Train-Test Split
               |
               v
      Create Regression Model
               |
               v
         Train the Model
          (model.fit)
               |
               v
       Predict Test Values
        (model.predict)
               |
               v
       Evaluate Performance
               |
               v
        Analyze and Improve
               |
               v
              End
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* NumPy

---

## 📊 Important Concepts

### 1. Features and Target

* **Features (X):** Two or more independent input variables.
* **Target (y):** The numerical output we want to predict.

### 2. Train-Test Split

Splits the dataset into training and testing sets to evaluate performance on unseen data.

### 3. Model Training

The model learns the coefficients and intercept from the training data.

### 4. Evaluation Metrics

* **MAE (Mean Absolute Error):** Average absolute prediction error.
* **MSE (Mean Squared Error):** Average squared prediction error.
* **RMSE (Root Mean Squared Error):** Square root of MSE, expressed in the target's units.
* **R² Score:** Measures model performance relative to predicting the target mean.

---

## ⚖️ Simple vs Multiple Linear Regression

| Feature         | Simple Linear Regression | Multiple Linear Regression          |
| --------------- | ------------------------ | ----------------------------------- |
| Input variables | One                      | Two or more                         |
| Formula         | ŷ = b₀ + b₁x             | ŷ = b₀ + b₁x₁ + ... + bₙxₙ          |
| Example         | Area → House Price       | Area + Bedrooms + Age → House Price |

---

## ✅ Advantages

* Easy to understand and implement.
* Uses multiple features for prediction.
* Coefficients help interpret feature relationships.
* Computationally efficient for many datasets.

## ⚠️ Limitations

* Assumes a linear relationship between features and target.
* Sensitive to outliers.
* Multicollinearity can make coefficients difficult to interpret.
* Performance may suffer when important relationships are nonlinear.

---

## 📚 Key Takeaways

* Multiple Linear Regression is a supervised learning algorithm.
* It predicts continuous numerical values.
* It uses two or more independent variables.
* `train_test_split()` helps evaluate the model on unseen data.
* `LinearRegression()` from Scikit-learn implements the algorithm.
* MAE, MSE, RMSE, and R² are commonly used evaluation metrics.

---

## 🚀 Learning Journey

This project is part of my Machine Learning learning journey, where I explore concepts step by step through practical implementation.

**One step a day leads to bigger outcomes!**
