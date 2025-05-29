# 🏠 Task 3: Linear Regression – House Price Prediction

## 📌 Objective
The objective of this task is to **implement and understand simple and multiple linear regression** using a real-world dataset. You'll learn how to preprocess data, train models, evaluate their performance using appropriate metrics, and interpret the regression coefficients.

---

## 🛠 Tools & Libraries Used
- Python
- [Pandas] – for data manipulation
- [Scikit-learn] – for model training and evaluation
- [Matplotlib] – for plotting and visualization

---

## 📁 Dataset
We used the **House Price Prediction Dataset**, which contains information about houses, including:

- **Numerical Features**: `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- **Categorical Features**: `mainroad`, `guestroom`, `basement`, `airconditioning`, `furnishingstatus`, etc.
- **Target Variable**: `price`

📥 **[Click here to download the dataset](#)**

---

## 🧪 Steps Performed

### 1. Import & Preprocess the Dataset
- Loaded the dataset using `pandas`
- Handled missing values (if any)
- Converted categorical features using one-hot encoding (`pd.get_dummies`)

### 2. Split Data into Train-Test Sets
- Used `train_test_split()` to divide the data (80% training, 20% testing)

### 3. Fit Linear Regression Model
- Applied `LinearRegression()` from `sklearn.linear_model`
- Trained the model on the training data

### 4. Evaluate the Model
Used the following metrics to assess model performance:
- **MAE**: Mean Absolute Error
- **MSE**: Mean Squared Error
- **R²**: Coefficient of Determination

### 5. Visualize & Interpret Results
- Plotted a regression line (for simple regression)
- Created a residual plot (for multiple regression)
- Interpreted model coefficients

---

## 📈 Example Evaluation Metrics

| Metric | Value (Example) |
|--------|------------------|
| MAE    | 124523.22        |
| MSE    | 2.13e+10         |
| R²     | 0.82             |

---

## 📊 Key Learnings
- How to preprocess real-world data for regression
- Simple vs Multiple Linear Regression
- Evaluation using MAE, MSE, R²
- Coefficient interpretation and residual analysis

---

## ▶️ How to Run

```bash
# Step 1: Clone or download this repository
# Step 2: Install required libraries
pip install pandas scikit-learn matplotlib

# Step 3: Run the Python script or Jupyter notebook
python linear_regression_house_price.py
