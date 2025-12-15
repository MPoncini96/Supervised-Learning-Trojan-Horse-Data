# Supervised Learning on the Trojan Horse Dataset

This project implements a full **supervised machine learning pipeline** to classify instances in the **Trojan Horse dataset**.  
The notebook walks through data preparation, model training, evaluation, and visualization using multiple ML algorithms.  
The goal is to compare classifier performance and understand which input features drive accurate predictions.

---

## Project Overview

This repository demonstrates a complete end-to-end ML workflow that includes:

- Data cleaning and preprocessing  
- Handling categorical & numerical features  
- Training and evaluating several classification algorithms  
- Generating confusion matrices and performance comparisons  
- Visualizing model behavior  
- Interpreting feature importance (tree-based models)

This project is designed to show practical ML engineering skills using real datasets and reproducible workflows.

---

## Pipeline Overview

### **1. Load & Clean Data**
- Import Trojan Horse dataset  
- Handle missing values  
- Encode categorical features (One-Hot / Label Encoding)  
- Normalize numerical input features (StandardScaler / MinMaxScaler)

### **2. Train/Test Split**
- Hold-out split for unbiased model evaluation  
- Ensures reproducibility with random states

### **3. Model Training (Classifiers Used)**
The following models are implemented and benchmarked:

- **Logistic Regression**  
- **Decision Tree**  
- **Random Forest**  
- **k-Nearest Neighbors (k-NN)**  
- **Support Vector Machine (SVM)**  
- **Naïve Bayes**  
- **Gradient Boosting / XGBoost**  
- **Simple Ensemble / Voting Classifier**

This allows comparison between linear, tree-based, distance-based, probabilistic, and boosting-based methods.

### **4. Evaluation**
- Accuracy, Precision, Recall, F1-Score  
- Confusion matrices for every classifier  
- ROC curves (optional)  
- Feature importance for tree-based models  
- Misclassification analysis

### **5. Visualization**
- Model performance bar charts  
- Confusion matrix heatmaps  
- Decision boundary visualizations (for 2-feature slices)  
- Feature importance plots

---

## 📊 Example Results Summary

| Model | Accuracy | Notes |
|-------|----------|-------|
| Logistic Regression | ~53.87% | Baseline |
| Random Forest | ~76.69% | Best overall, stable performance |
| Decision Tree | ~64.90% | Good performance |
| k-NN | ~67.17% | Sensitive to scaling |
| Naïve Bayes | ~51.24% | Fast but innacurate due to correlated features |
| Ensemble | ~68.26% | Competitive and stable |

*(Replace X% with your actual results if desired.)*

---

## Tech Stack

- **Python**
- **scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## Skills Demonstrated

- End-to-end supervised ML workflow  
- Data preprocessing and feature engineering  
- Training & comparing multiple classifiers  
- Model evaluation and interpretation  
- Visualization of ML outputs  
- Reproducible Jupyter Notebook analysis  

These skills directly map to real-world ML engineering and data science roles.

---
