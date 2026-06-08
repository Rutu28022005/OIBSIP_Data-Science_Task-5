# Task 5 - Sales Prediction using Machine Learning

## Objective

The objective of this project is to predict product sales based on advertising expenditures across different marketing channels.

Advertising platforms considered:

- TV
- Radio
- Newspaper

---

## Dataset

The dataset contains:

- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget
- Sales

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Steps Performed

### 1. Data Loading
- Imported advertising dataset.

### 2. Data Exploration
- Checked dataset structure.
- Verified missing values.

### 3. Data Visualization
- Generated:
  - Correlation Heatmap
  - Pair Plot

### 4. Feature Selection
- Selected:
  - TV
  - Radio
  - Newspaper

as input variables.

### 5. Train-Test Split
- Divided dataset into training and testing sets.

### 6. Model Building
- Implemented Linear Regression model.

### 7. Model Training
- Trained the model using advertising data.

### 8. Model Evaluation
- Calculated:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

### 9. Visualization
- Created Actual vs Predicted Sales scatter plot.

### 10. Future Prediction
- Predicted sales for new advertising expenditure values.

---

## Outcome

- Successfully predicted sales using advertising budgets.
- Linear Regression demonstrated strong predictive capability.
- Identified relationships between marketing expenditure and sales performance.

---

## Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
