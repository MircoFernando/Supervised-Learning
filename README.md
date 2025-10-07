# Supervised-Learning DONE

# 🧠 Titanic Survival Prediction — Machine Learning from Scratch vs Library Implementations

## 📘 Overview

This project focuses on predicting the survival of passengers aboard the Titanic using supervised machine learning techniques. The main goal is to compare models developed **from scratch** (manual implementation using core Python, NumPy, and Pandas) with those developed using **machine learning libraries** (such as Scikit-learn).  

The study aims to:
- Understand how model parameters and regularization affect learning.
- Evaluate ensemble methods (Bagging & Boosting) and their impact on model performance.
- Compare the performance between scratch-built and library-based models using standard evaluation metrics.

---

## 🧩 Project Objectives

1. **Data Understanding & Preprocessing**
   - Load and clean the Titanic dataset.
   - Perform encoding for categorical variables and normalization of numerical features.
   - Split the dataset into training and testing sets for unbiased evaluation.

2. **Model Implementation**
   - Implement **Logistic Regression (No Penalty, L1, L2)** from scratch and with Scikit-learn.
   - Implement **Decision Tree Classifier** from scratch.
   - Build **Bagging** and **Boosting** ensemble models using Scikit-learn.

3. **Model Evaluation**
   - Evaluate models using metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
   - Compare and interpret results between custom implementations and library implementations.
   - Visualize results using confusion matrices, ROC curves, and comparative bar charts.

4. **Reporting**
   - Present findings, performance analysis, and future recommendations.
   - Deliver a concise yet comprehensive report (`D_report.pdf`).

---

## 🧮 Algorithms Implemented

| Category | Models |
|-----------|---------|
| **From Scratch** | Logistic Regression (No penalty, L1, L2), Decision Tree, Bagging |
| **Using Scikit-learn** | Logistic Regression, Decision Tree, Bagging, AdaBoost (Boosting) |

Each model is trained, tuned, and evaluated using the same dataset split to ensure fair comparison.

---

## ⚙️ Data Preprocessing Steps

1. Handled missing values and outliers.
2. Encoded categorical variables such as `Sex` and `Embarked`.
3. Normalized numerical features like `Age` and `Fare`.
4. Split dataset into training and testing sets (80/20 split).
5. Exported train/test splits into `.csv` files for model reusability.

---

## 🧠 Evaluation Metrics

| Metric | Description |
|---------|--------------|
| **Accuracy** | Measures the proportion of correct predictions overall. |
| **Precision** | Measures how many predicted positives are actually positive. |
| **Recall (Sensitivity)** | Measures how many actual positives are correctly identified. |
| **F1-Score** | Harmonic mean of Precision and Recall. |
| **ROC-AUC** | Measures the area under the ROC curve, showing classifier separability. |

---

## 📊 Key Results Summary

-- Please review the D_report for the overall Analysis
---

## 📈 Visualizations

The following plots were generated for model evaluation:
- **Confusion Matrix:** Shows the distribution of predicted vs actual classes.
- **ROC Curve:** Evaluates the trade-off between true positive rate and false positive rate.
- **Bar Chart Comparison:** Displays accuracy and F1-score comparison between all models (scratch vs library).

---
This project demonstrated the implementation and comparison of several supervised machine 
learning algorithms, both from scratch and using library-based methods, on the Titanic 
Survival dataset. Through systematic evaluation, it was observed that while models 
developed from scratch provided valuable learning on the inner workings of algorithms, the 
library implementations delivered higher efficiency, stability, and ease of experimentation. 
Among logistic regression variants, L2 regularisation achieved the best overall performance, 
balancing accuracy and generalisation. Decision Trees offered interpretability but tended to 
overfit when made too deep, whereas bagging and boosting improved stability and predictive 
power through ensemble learning. 
Overall, the findings highlight that no single approach is universally superior; rather, the 
choice depends on the trade-off between interpretability, computational cost, and predictive 
accuracy. The project also underlines the importance of preprocessing, regularisation, and 
ensemble methods in building robust machine learning models.



