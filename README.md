# 🛣️ Intelligent Classification of Rural Infrastructure Projects (PMGSY)

This project aims to build a machine learning model that classifies rural infrastructure projects into the appropriate **PMGSY (Pradhan Mantri Gram Sadak Yojana)** scheme based on their physical and financial attributes. The project is developed as part of an IBM Cloud Lite-based AI/ML challenge.

---

## 📌 Objective

To intelligently classify road and bridge projects using ML techniques to support automated infrastructure planning and policy-making under PMGSY schemes.

---

## 🧠 ML Approach

### ✅ Preprocessing
- Missing value imputation using mode
- Label encoding for categorical features
- Standardization using `StandardScaler`

### ✅ Models Trained
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- Support Vector Machine
- XGBoost

### ✅ Evaluation
- Accuracy and classification report
- Best Model: **XGBoost** with ~91.3% accuracy on validation set

---

## 📁 Project Structure

```
.
├── PMGSY_DATASET.csv           # Input dataset
├── pmgsy_ml_classification.py  # Main ML script
├── requirements.txt            # dependencies
├── README.md                   # Project overview
```

---

## 🚀 Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pmgsy-classification.git
   cd pmgsy-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:
   ```bash
   python pmgsy_ml_classification.py
   ```

---

## 📊 Results

- Best performing model: **XGBoost**
- Accuracy: ~91.3%
- Multiclass classification performance evaluated using:
  - Precision
  - Recall
  - F1-Score

---

## 🛠️ Hyperparameter Tuning (Optional)

You can improve the performance of models (like SVM, Random Forest, XGBoost) using `GridSearchCV`. Code is included and commented inside the script for experimentation.

---

## ☁️ IBM Cloud Lite Compatibility

- This solution can be deployed on IBM Cloud Lite using:
  - Watson Studio (Notebook or AutoAI)
  - Flask app deployed with IBM Cloud App service


