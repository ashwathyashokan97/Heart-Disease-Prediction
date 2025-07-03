
# Heart Disease Prediction using PySpark

This project is part of the **Big Data Frameworks (BDM 3014)** coursework and demonstrates how to build a scalable and interpretable machine learning model for predicting heart disease using **PySpark** and **Pandas**.

---

## 📊 Project Overview

- **Objective**: Predict the presence of heart disease using medical attributes.
- **Dataset**: UCI Cleveland Heart Disease dataset (303 samples, 15 features).
- **Tech Stack**: PySpark, Pandas, Matplotlib, Scikit-learn
- **ML Models Used**:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier

## 📁 Project Structure
heart-disease-pyspark
├── 📓 Mid_Term_Project.ipynb # Jupyter notebook with full code
├── 📄 Final_Report.pdf # Comprehensive report describing all steps
├── 📊 Visualizations/ # Model performance charts & confusion matrix
├── 📄 presentation.pptx # 10-slide class presentation
├── 📄 requirements.txt # Required packages
└── 📄 README.md # This file

---

## 📈 Model Performance Summary

| **Metric**     | **Logistic Regression** | **Random Forest** | **Gradient Boosting** |
|----------------|--------------------------|--------------------|------------------------|
| Accuracy       | 85.2%                    | 83.6%              | 77.0%                  |
| F1-Score       | 85.2%                    | 83.6%              | 77.0%                  |
| Sensitivity    | 82.1%                    | N/A                | N/A                    |
| Specificity    | 87.9%                    | N/A                | N/A                    |
| Interpretability | High                  | Moderate + Feature Importance | Moderate          |
| Final Use      | Baseline                 | ✅ Final Choice     | ❌ Rejected            |

✔️ **Final Model**: Random Forest Classifier (chosen for balanced performance and interpretability)

---

## 📌 Key Features

- Mean imputation for missing values
- Label encoding and vector assembly
- Feature scaling using StandardScaler
- Logistic, Random Forest, and Gradient Boosting classifiers
- Model evaluation with accuracy, F1, sensitivity, and specificity
- Confusion matrix and top feature importance visualization
- Side-by-side model performance dashboard

---

## 💻 How to Run

> ✅ Recommended: Google Colab or local Jupyter Notebook with PySpark setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-pyspark.git
   cd heart-disease-pyspark




