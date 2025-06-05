# 🤖 Breast Cancer Classification using Support Vector Machines (SVM)

This project demonstrates the use of **Support Vector Machine (SVM)** classifiers (Linear and RBF kernels) to detect breast cancer using the popular **Breast Cancer Wisconsin Dataset**. The goal is to classify tumors as **Malignant (1)** or **Benign (0)** based on diagnostic features.

---

## 📁 Dataset

- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Samples**: 569
- **Features**: 30 numerical measurements from cell nuclei
- **Target**:  
  - 0 = Benign  
  - 1 = Malignant

---

## ✅ Workflow

### 🔹 Step 1: Data Loading
- Loaded the dataset using sklearn

### 🔹 Step 2: Preprocessing
- Scaled the features using `StandardScaler` for better SVM performance

### 🔹 Step 3: Model Training
- Trained two SVM models:
  - Linear Kernel
  - RBF Kernel (non-linear)

### 🔹 Step 4: Evaluation
- Evaluated models using:
  - Confusion Matrix
  - Classification Report
  - Accuracy Score
  - Cross-validation (5-fold)

---

## 📊 Results

| Model        | Accuracy | Comments |
|--------------|----------|----------|
| Linear SVM   | ~96%     | Simple & interpretable |
| RBF SVM      | ~98%     | Captures complex non-linear patterns |
| Cross-Val (RBF) | ~97.8% | Stable across folds |

---

## 📂 Files in Repo

- `svm_breast_cancer.ipynb`: Complete code with evaluation
- `README.md`: Project documentation
- `breast-cancer.csv
