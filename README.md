# 🌳 PRODIGY_DS_03 – Decision Tree Classifier on Bank Marketing Data

## ✅ Task Objective

Build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on their **demographic and behavioral data**.

The model is trained on the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

---

## 📁 Task Description

This project involves:
- Data loading and preprocessing
- Feature encoding and normalization
- Building and visualizing a decision tree
- Model evaluation using metrics such as accuracy, precision, recall, and F1-score

---

## 🗃️ Dataset Used

- **Name:** Bank Marketing Dataset  
- **Source:** [UCI Repository – Bank Marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **File:** `bank-full.csv`

> The dataset contains 17 input features (e.g., age, job, marital status, duration of last contact) and a target variable `y` indicating whether the client subscribed to a term deposit.

---

## 🛠️ Tools & Libraries Used

- `pandas`, `numpy` – data handling  
- `scikit-learn` – model building & evaluation  
- `matplotlib`, `seaborn` – visualization  
- `graphviz` or `dtreeviz` (optional) – decision tree visualization

---

## 📊 Steps Performed

1. **Data Cleaning**
   - Handled missing values
   - Dropped or transformed irrelevant features

2. **Encoding**
   - Used Label Encoding or One-Hot Encoding for categorical variables

3. **Model Training**
   - Split dataset into training and test sets
   - Trained `DecisionTreeClassifier` from `sklearn`

4. **Visualization**
   - Visualized the decision tree structure
   - Plotted feature importances

5. **Evaluation**
   - Evaluated model using:
     - Accuracy
     - Confusion Matrix
     - Precision, Recall, F1-score
     - ROC Curve (optional)

---

## 📈 Results

- **Model Accuracy:** ~X% (fill in based on your model)
- **Top Influential Features:** `duration`, `month`, `contact`, etc.

> Short call durations and previous outcomes were significant predictors in client decision-making.

---

## 📌 Key Learnings

- How decision trees work for classification tasks  
- Handling and encoding categorical data effectively  
- Importance of interpreting tree-based models and their decisions  
- Avoiding overfitting by controlling tree depth and pruning
