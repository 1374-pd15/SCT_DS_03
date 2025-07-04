# 🌳 Task 03: Bank Marketing – Decision Tree Classification  
**SkillCraft Data Science Internship**

---

## 📌 Objective  
The objective of this task is to build a **Decision Tree Classifier** using the **Bank Marketing Dataset** to predict whether a customer will subscribe to a term deposit (`yes` or `no`). This task highlights both model building and interpretability using tree-based techniques.

---

## 🧠 Data Science Concepts Applied

### 1. Data Preprocessing
- Loaded and explored the **bank marketing dataset** (`bank_full.csv`)
- Converted all categorical features (e.g., `job`, `marital`, `education`) into numeric form using:
  - `LabelEncoder` from `sklearn.preprocessing`
- Removed or encoded non-informative features such as `contact`, `duration`, or `pdays` (optional)

### 2. Exploratory Data Analysis (EDA)
- Used visualizations to understand relationships between:
  - `job`, `education`, `marital` vs `y` (term deposit subscription)
- Analyzed class imbalance between `yes` and `no` responses

### 3. Decision Tree Modeling
- Applied `DecisionTreeClassifier` from `scikit-learn`
- Trained the model on encoded features
- Split the data into training and testing sets (e.g., 80/20)
- Visualized the model with:
  - `sklearn.tree.plot_tree()` for basic structure

### 4. Model Evaluation
- Evaluated predictions using:
  - **Accuracy score**
  - **Confusion matrix**
  - **Classification report** (precision, recall, F1-score)
- Assessed **model interpretability** using tree visualization

---

## 📁 Files Included

| File Name                                  | Description                                |
|-------------------------------------------|--------------------------------------------|
| `SCT_DS_03.ipynb, SCT_DS_03.html` | Full implementation with code, EDA, and model |
| `bank_full.csv`                                 | Bank Marketing dataset from UCI Repository |
| `README.md`                                | This documentation file                    |

---

## 🛠️ Libraries Used

- python
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

---

## 📊 Key Visualizations
- 📊 Bar charts showing subscription count by job and marital status
- 🥧 Pie chart representing the proportion of customers who subscribed (yes vs no)
- 🌳 Full decision tree diagram using dtreeviz — interactively color-coded by feature splits and target classes
- ⭐ Feature importance plot generated from the trained tree model, showing which inputs mattered most

---

## 💡 Insights & Learning
- Decision trees provide excellent model transparency, making it easier to explain decisions to non-technical stakeholders.
- Categorical data must be preprocessed properly to avoid incorrect splits and misleading inferences.
- The target variable is imbalanced (many more “no”s than “yes”s), which should influence model selection and metric interpretation.

🧠 "A good model doesn’t just predict well — it should also explain why."

---

## Summary
This task emphasized the importance of:
- ✅ Data preprocessing for categorical machine learning problems
- ✅ Using decision trees for both prediction and interpretation
- ✅ Evaluating classifiers using proper metrics, especially when working with imbalanced datasets

---
