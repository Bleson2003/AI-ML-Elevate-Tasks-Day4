# 🚀 Task 4: Binary Classification with Logistic Regression

This project is part of the **AI & ML Internship** and involves building a binary classifier using **Logistic Regression** on a provided dataset `data.csv`.

---

## 🧠 Objective

To understand and implement logistic regression for **binary classification**, including:

- Training and testing a model.
- Evaluating performance with standard metrics.
- Tuning thresholds and visualizing the sigmoid behavior.

---

## 📂 Dataset

The dataset used is `data.csv`, which contains features for classification and a **binary target** label.

> 📌 **Assumptions**:
> - The **last column** in the dataset is the target variable.
> - No missing or non-numeric values are present after cleaning.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📈 Model Pipeline

1. 📥 **Load Data** using `pandas`
2. 🧹 **Clean Data** using `dropna()`
3. 🔀 **Split** features (`X`) and target (`y`)
4. ✂️ **Train-Test Split** using `train_test_split()`
5. ⚖️ **Standardize Features** using `StandardScaler`
6. 🤖 **Train Model** using `LogisticRegression`
7. 📊 **Evaluate Model**:
   - Confusion Matrix
   - Classification Report
   - Precision and Recall
   - ROC-AUC Curve
8. ⚙️ **Threshold Tuning**
9. 🧠 **Visualize Sigmoid Function**

---

## 📊 Outputs & Results

- ✅ Confusion matrix (with heatmap)
- ✅ Classification report (Accuracy, Precision, Recall, F1-score)
- ✅ ROC Curve with AUC score
- ✅ Custom threshold confusion matrix
- ✅ Sigmoid function plot

---

## 🧪 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC-AUC**

---

## 📎 How to Run

1. Open the provided Google Colab notebook.
2. When prompted, upload `data.csv`.
3. Run all cells to execute the full logistic regression pipeline.

---

## 📌 Interview Questions Covered

- What is logistic regression and how does it differ from linear regression?
- What is the sigmoid function?
- What are precision and recall?
- What is the ROC-AUC curve?
- What is a confusion matrix?
- How to handle class imbalance?
- How to choose a threshold?
- Can logistic regression be used for multi-class problems?

---

## 📁 Project Structure

