
````markdown
# 👥 HR Analytics: Employee Attrition Prediction

This project applies **Logistic Regression** to analyze and predict employee attrition using historical HR data. It explores how various factors like **salary**, **satisfaction level**, and **promotion history** influence an employee's decision to leave.

---

## 📊 Dataset

The dataset `HR_comma_sep.csv` includes:
- `satisfaction_level`
- `last_evaluation`
- `number_project`
- `average_montly_hours`
- `time_spend_company`
- `Work_accident`
- `promotion_last_5years`
- `salary`
- `left` (Target: 1 = left company, 0 = stayed)

---

## 📦 Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hr-employee-attrition.git
   cd hr-employee-attrition
````

2. Open the notebook:

   ```bash
   jupyter notebook HR-analytics.ipynb
   ```

3. Or run as a script (if converted):

   ```bash
   python hr_attrition_predictor.py
   ```

---

## 🔍 Project Highlights

* ✅ Load and explore HR dataset
* 📊 Visualize salary vs. attrition using bar charts
* 🤖 Train a Logistic Regression model
* 📈 Predict and interpret whether employees will leave

---

## 🧠 Model Used

* **Logistic Regression** (`sklearn.linear_model.LogisticRegression`)
* Input features: e.g., salary (converted to numerical), satisfaction, promotions
* Output: Probability of an employee leaving

---

## 📈 Sample Output

```python
plt.bar(df.salary, df.left)
```

* Shows attrition rate by salary level
* Additional visualizations can be added to explore other features

---

## ✅ Result

* Helps HR understand patterns in employee resignations
* Can assist in designing better employee retention strategies

---

## 📂 File Structure

```
hr-employee-attrition/
│
├── HR_comma_sep.csv                # Dataset
├── HR-analytics.ipynb              # Main analysis notebook
├── README.md                       # Project overview and usage
```

---

## 🤝 Contributing

Feel free to fork and submit pull requests. Suggestions for improvements are always welcome!

---

## 📜 License

[MIT License](LICENSE)

---
