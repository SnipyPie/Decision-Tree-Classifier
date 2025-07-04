# 🌳 Customer Purchase Prediction using Decision Tree Classifier

This project demonstrates a complete workflow to build a **Decision Tree Classifier** to predict whether a customer will purchase a product or service, based on **demographic** and **behavioral** data.

---

## 📂 Dataset

- **Source**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)  
- **File Used**: `bank.csv`
- **Target Column**: `y` — indicates whether the client subscribed to a term deposit (yes/no)

---

## 🎯 Objective

To analyze customer information and build a model that classifies whether a client will **purchase the product** or not.

---

## ✅ Workflow

1. **Load & Inspect Data**
   - Handled special delimiters (`;`)
   - Checked null values and class balance

2. **Data Preprocessing**
   - Converted categorical data using one-hot encoding
   - Converted target values to binary (True/False)
   - Split dataset into training and testing sets (80/20)

3. **Model Training**
   - Used `DecisionTreeClassifier` from `scikit-learn`
   - Trained with `random_state=42` for reproducibility

4. **Evaluation**
   - Calculated Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix for True/False prediction balance

5. **Visualization**
   - Visualized the decision tree using `graphviz`
   - Installed Graphviz system tool for rendering `.dot` files

---

## 📊 Results

- **Accuracy**: `88.06%`
- **Precision (for yes)**: `0.45`
- **Recall (for yes)**: `0.50`
- **Confusion Matrix**:
