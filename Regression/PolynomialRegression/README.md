# Polynomial Regression – Position vs Salary Prediction

**Goal:** Use polynomial regression to model and predict salaries based on position level, capturing the non-linear relationship between role seniority and compensation.

**Dataset:** `Position_Salaries.csv`  
(Features: Position Level → Salary)

**Tech stack:** Python, Pandas, Matplotlib, Scikit-learn, NumPy, Seaborn

---

## 🔧 Steps Performed:

- Visualized the original data to assess linearity
- Applied polynomial transformation (degree = 2 to 4) using `PolynomialFeatures`
- Fitted both linear and polynomial regression models
- Compared model predictions visually and numerically

---

## 📊 Result:

The polynomial regression model significantly improved fit over the simple linear model, capturing the curvature in the salary progression across position levels.

---

## 📁 Files Included:

- `PolynomialRegression.ipynb` – notebook with full code and plots
- `Position_Salaries.csv` – original dataset
- (Optional) `regression_plot.png` – visualization of polynomial fit

