# AI-ML-INTERNSHIP-DAY-4
# 🧠 Breast Cancer Classification using Logistic Regression

This project focuses on building a binary classification model using Logistic Regression to predict whether a tumor is malignant or benign based on the Breast Cancer Wisconsin dataset.

---

## 🎯 Objective

To develop a machine learning classifier that can assist in the early detection of breast cancer using features computed from digitized images of breast mass.

---

## 📂 Dataset

- *Source*: UCI Machine Learning Repository via Kaggle
- *Name*: Breast Cancer Wisconsin (Diagnostic) Data Set
- *Features*: 32 numerical features computed from images
- *Target*: Diagnosis (Malignant = 1, Benign = 0)

---

## 🛠 Tools and Technologies

- Python
- Jupyter Notebook
- Libraries:
  - pandas, numpy – data manipulation
  - matplotlib, seaborn – data visualization
  - scikit-learn – model building and evaluation
  - kagglehub – dataset download

---

## 📊 Project Workflow

### 1. Data Loading
- Used kagglehub to download the dataset.
- Loaded data into a Pandas DataFrame.

### 2. Data Exploration & Cleaning
- Checked for missing/null values.
- Explored dataset structure and summary statistics.
- Dropped irrelevant columns like Unnamed: 32 and id.

### 3. Visualization
- Used correlation heatmaps to observe feature relationships.
- Created pair plots and histograms for feature distributions.

### 4. Feature Engineering
- Converted categorical labels into binary values (M → 1, B → 0).
- Standardized features using StandardScaler.

### 5. Model Building
- Split data into training and testing sets.
- Built and trained a *Logistic Regression* model.

### 6. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## ✅ Results

- *Accuracy Score*: ~97% (Exact value in notebook)
- The model performs well in distinguishing between malignant and benign cases.

---
