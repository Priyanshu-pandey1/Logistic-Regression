# 💓 Heart Disease Prediction using Logistic Regression

This project focuses on **Binary Classification** to predict the likelihood of heart disease in patients. Moving beyond regression, this implementation explores classification metrics and the importance of data scaling in predictive modeling.

---

## 📌 Project Overview
Using the UCI Heart Disease dataset, I implemented a Logistic Regression model to classify patients based on medical attributes like age, sex, cholesterol levels, and maximum heart rate.



---

## 🛠️ Technical Highlights

### **1. Data Preprocessing**
* **Exploratory Data Analysis (EDA):** Analyzed target distribution (133 Positive vs 109 Negative cases).
* **Feature Scaling:** Applied `StandardScaler` to normalize features, ensuring the Logistic Regression model converges efficiently.
* **Categorical Handling:** Used `pd.get_dummies` and mapping for feature consistency.

### **2. Model Implementation**
* **Algorithm:** Logistic Regression (with `max_iter=5000` for convergence).
* **Training:** 80/20 Train-Test split using a fixed `random_state` for reproducibility.

### **3. Advanced Evaluation Metrics**
In medical diagnostics, **Recall** is often more important than Accuracy. This project evaluates:
* **Confusion Matrix:** To visualize True Positives vs. False Negatives.
* **Recall & F1-Score:** To measure the model's ability to identify actual heart disease cases.

---

## 📊 Performance Results

| Metric | Score |
| :--- | :--- |
| **Accuracy** | **88.52%** 🚀 |
| **Precision** | **87.87%** |
| **Recall** | **90.62%** |
| **F1-Score** | **0.892** |

### **Confusion Matrix Analysis:**
```text
[[25  4]  <- True Negatives | False Positives
 [ 3 29]] <- False Negatives | True Positives
```
## 🛠️ Tech Stack
- **Language:** Python 🐍
- **Libraries:** Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib
- **Tooling:** Jupyter Notebook

## 📂 Repository Structure
- `Logistic_Regression.ipynb`: Full implementation from EDA to Evaluation.
- `heart.csv`: Dataset containing medical records for heart disease prediction.
- `README.md`: Project documentation and results.

---

## 🔗 Connect with me
Let's discuss Data Science and Machine Learning!
- **LinkedIn:** [Priyanshu Pandey](https://www.linkedin.com/in/priyanshu-pandey-data/)
