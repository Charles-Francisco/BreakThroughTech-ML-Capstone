# BreakThroughTech-ML-Capstone

## 📖 Overview
- **Program:** Break Through Tech ML Summer Program  
- **Goal:** Apply machine learning techniques to solve a real-world problem  
- **Focus Areas:** Data preprocessing, exploratory data analysis, feature engineering, model development, and evaluation  

---

## 📊 Results
- While both models turned out to be good, the **Random Forest** model was superior to the **Linear Regression** model. It achieved a lower RMSE and higher R², indicating more accurate predictions and a better fit to the data.  
- The `param_grid` values used for hyperparameter tuning were kept sparse. Expanding them likely would have improved the Random Forest model further, but GridSearchCV became prohibitively slow with too many parameter options.  
- **Performance Comparison:**  
  - **Linear Regression:** Slight underfitting. Captures global trends but fails to model non-linear patterns.  
  - **Random Forest:** Captures more variance and performs better on test data, though it mildly overfits.  
  - **Error Rates:** Lower for Random Forest, resulting in more accurate predictions overall.  
- In short, **Linear Regression** showed low variance but high bias, while **Random Forest** struck a balance between bias and variance, albeit with slight overfitting.

---

## ⚙️ Tools & Libraries
- Python  
- pandas, NumPy  
- scikit-learn  
- matplotlib, seaborn  
- Jupyter Notebook  
