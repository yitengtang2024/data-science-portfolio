# Multiple Linear Regression – Startup Profit Prediction

**Goal:** Predict the profit of startups based on multiple independent variables such as R&D Spend, Administration, Marketing Spend, and State (categorical feature).

**Dataset:** `50_Startups.csv`  
(Includes features: R&D Spend, Administration, Marketing Spend, State → Profit)

**Tech stack:** Python, Pandas, Scikit-learn, Matplotlib, NumPy

---

## 🔧 Steps Performed:

- Loaded and inspected the dataset
- Applied One-Hot Encoding to the categorical 'State' column using `ColumnTransformer`
- Built a multiple linear regression model using `LinearRegression`
- Split data into training and testing sets
- Evaluated predictions on the test set

---

## 📊 Result:

The model was able to learn the relationship between expenditures and profit. Feature encoding and proper preprocessing enabled the linear regression model to generalize well to unseen data.

---

## 📁 Files Included:

- `MultipleLinearRegression.ipynb` – Jupyter notebook with full implementation
- `50_Startups.csv` – dataset used
- (Optional) regression residuals chart / feature coefficients plot

