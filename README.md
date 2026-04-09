# XAI-XGBoost: Explainable Machine Learning Framework for Multi-Class Electrical Fault Detection

Official implementation of **XAI-XGBoost**, a SHAP-based explainable machine learning framework developed for robust **multi-class electrical fault detection and classification**.
This repository provides a complete end-to-end pipeline including data preprocessing, outlier removal, statistical feature engineering, class balancing, comparative model evaluation, and **Explainable AI (XAI)** analysis using SHAP.

The proposed framework is designed to ensure **high predictive accuracy, model robustness, and interpretability**, making it suitable for research applications in **electrical engineering, smart grid monitoring, and fault diagnosis systems**.

---

## 📌 Research Overview

Electrical fault detection plays a critical role in ensuring the safety, reliability, and operational stability of modern power systems.
This work introduces an **interpretable XGBoost-based classification framework** that combines advanced machine learning with SHAP-driven explainability to accurately detect and classify multiple fault categories.

The workflow includes:

* Raw signal preprocessing
* Missing value handling
* Isolation Forest-based outlier removal
* PCA visualization
* Statistical feature extraction
* SMOTE-based class balancing
* Multi-model benchmarking
* Statistical significance testing
* SHAP explainability analysis

---

## ⚙️ Methodology Pipeline

The proposed framework follows the steps below:

1. **Dataset Loading and Merging**
2. **Signal Preprocessing**
3. **Outlier Removal using Isolation Forest**
4. **Feature Engineering**
   * RMS
   * Mean
   * Standard deviation
   * Peak-to-peak
   * Energy
5. **Fault Labeling**
6. **SMOTE for class balancing**
7. **Training and comparison of 11 ML models**
8. **Best model selection (XGBoost)**
9. **SHAP-based explainability**
10. **Statistical significance testing using paired t-test**

---

## 🤖 Machine Learning Models Evaluated

The following models were trained and compared:

* Logistic Regression
* KNN
* SVM
* Decision Tree
* Random Forest
* Extra Trees
* Gradient Boosting
* AdaBoost
* **XGBoost (Best Performing Model)**
* LightGBM
* CatBoost

---

## 📊 Explainable AI (SHAP)

To improve model transparency and interpretability, this framework integrates **SHAP (Shapley Additive Explanations)** for:

* Global feature importance
* Local prediction explanation
* Model decision visualization
* Fault-sensitive feature contribution analysis

This enhances trustworthiness and supports practical deployment in fault diagnosis systems.

---

## 📈 Output Results

The repository includes:

* Confusion matrices
* ROC curves
* Macro-average AUC
* Feature importance ranking
* SHAP summary plots
* Prediction tables
* Statistical significance analysis

---

## 🚀 Reproducibility

This repository is designed to support **research reproducibility and transparency**.
All preprocessing steps, model training, evaluation metrics, and explainability analyses are fully reproducible.

---

## 📚 Citation

If you use this work in your research, please cite the corresponding paper.

---

## 👨‍🔬 Author

**Sourav Sana**
B.Sc. in Electrical and Electronic Engineering
Research Focus: Machine Learning, Explainable AI, Medical & Signal Processing, Fault Diagnosis
