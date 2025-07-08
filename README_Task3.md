# 🌳 Task 3: Decision Tree Classifier - Bank Marketing Dataset

## 📌 Objective

Build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit (**target: `y`**) based on their **demographic** and **behavioral** attributes.

---

## 🗂️ Dataset

- **Source**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **File used**: `bank.csv`
- **Target Variable**: `y` (yes/no - term deposit subscribed)

### 🔑 Key Features:
- `age`, `job`, `marital`, `education`, `default`, `balance`, `housing`, `loan`, `contact`, `day`, `month`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`

---

## 🧹 Data Cleaning

- Handled missing values (none found).
- **Encoded categorical features** using Label Encoding.
- **Split** dataset into features (`X`) and label (`y`).
- Performed a **Train-Test Split** (80-20).

---

## 🤖 Model Building

- Used **DecisionTreeClassifier** from `sklearn.tree`.
- Parameters tuned: `max_depth=5` for clarity and interpretability.
- Fitted model on training data and made predictions on test data.

---

## 📊 Evaluation Metrics

- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1)
- **Confusion Matrix**
- **Decision Tree Visualization**

---

## 📈 Sample Output

![Decision Tree](plots/decision_tree.png)

> *(Add your actual plot image in a `plots/` folder and update the path)*

---

## 🧠 Observations

- The decision tree captured patterns in features like `duration`, `contact`, `poutcome`, and `previous`.
- The model was able to predict customer subscription behavior with reasonable accuracy.
- `duration` was one of the most important features influencing the prediction.

---

## 🛠️ Tools & Libraries Used

- Python (Google Colab)
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 👩‍💻 Done By

**Shruti Sharma**  
B.Tech CSE (AI & ML) | Data Science Intern at SkillCraft  
Chandigarh University

---

## 📌 Note

This task can be extended further by:
- Performing **Hyperparameter Tuning** (GridSearchCV).
- Comparing with other models like Random Forest or Logistic Regression.
- Deploying using Streamlit or Flask.
