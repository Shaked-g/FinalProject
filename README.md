<h1> Machine Learning Analysis of Enteral Feeding Intolerance
  
-Shaked Gofin </h1>


## Project Goal
The goal of this project is to apply machine learning techniques to data collected from real-life patients to gain insights into Enteral Feeding Intolerance (EFI). The aim is to assist doctors in making more data-driven decisions regarding treatment.

## Introduction
Enteral Feeding Intolerance (EFI) refers to the difficulty or adverse reactions experienced when receiving nutrition directly into the stomach or small intestine for clinical reasons. EFI can lead to poor outcomes, increased morbidity, and longer ICU stays. However, there is no universally accepted definition of EFI. By leveraging machine learning, I aim to identify distinct patient subgroups and correlating features related to EFI.

## Table of Contents
1. [Data Overview](#data-overview)
2. [Machine Learning](#machine-learning)
   - [Train-Test Split](#train-test-split)
     - [Stratifying](#stratifying)
   - [Logistic Regression](#logistic-regression)
     - [Evaluation](#evaluation)
     - [AUC Curve](#auc-curve)
     - [Confidence Interval](#confidence-interval)
   - [Random Forest Classifier](#random-forest-classifier)
     - [Evaluation](#evaluation-1)
     - [AUC Curve](#auc-curve-1)
     - [Feature Importance](#feature-importance)
     - [SHAP Values](#shap-values)
       - [SHAP Summary Plots](#shap-summary-plots)
       - [SHAP Feature Dependence Plot](#shap-feature-dependence-plot)
     - [Generating the Model on Selected Features](#generating-the-model-on-selected-features)
       - [Evaluation](#evaluation-2)
       - [AUC Curve](#auc-curve-2)
   - [XGBoost - Extreme Gradient Boosting](#xgboost---extreme-gradient-boosting)
     - [Evaluate Predictions](#evaluate-predictions)
     - [AUC Curve](#auc-curve-3)
     - [Grid Search Cross-Validation](#grid-search-cross-validation)
       - [Evaluation](#evaluation-3)
       - [Feature Importance](#feature-importance-1)
       - [AUC Curve](#auc-curve-4)
       - [SHAP Summary Plots](#shap-summary-plots-1)
   - [Joint AUC ROC Curve](#joint-auc-roc-curve)
   - [Decision Tree](#decision-tree)
3. [Unsupervised Learning](#unsupervised-learning)
   - [KMeans](#kmeans)
   - [Mean Shift Clustering](#mean-shift-clustering)
4. [kcal Data Set](#kcal-data-set)
   - [KMeans](#kmeans-1)
     - [Visualizing High-Dimensional Clusters](#visualizing-high-dimensional-clusters)
       - [PCA - Principal Component Analysis](#pca---principal-component-analysis)
       - [2D](#2d)
       - [3D](#3d)
     - [Compared To Old Data Set](#compared-to-old-data-set)

## Data Overview
This section covers the initial exploration and cleaning of the dataset, focusing on the first three days of patients' ICU stays. See [Data Overview](Final%20Project.ipynb#data-overview) in the notebook for details.

## Machine Learning
### Train-Test Split
- **Stratifying:** Ensured a balanced representation of classes in training and testing sets. See [Train-Test Split](Final%20Project.ipynb#train-test-split) in the notebook.

### Logistic Regression
- **Evaluation:** Assessed model performance using various metrics. See [Logistic Regression](Final%20Project.ipynb#logistic-regression) for more details.
- **AUC Curve:** Analyzed the ROC curve to evaluate model discriminative ability.
- **Confidence Interval:** Estimated the confidence intervals for predictions.

### Random Forest Classifier
- **Evaluation:** Comprehensive evaluation of model performance. See [Random Forest Classifier](Final%20Project.ipynb#random-forest-classifier).
- **AUC Curve:** ROC curve analysis for model performance.
- **Feature Importance:** Identified and ranked features by their contribution.
- **SHAP Values:** Used SHAP values for model interpretability.
  - **SHAP Summary Plots:** Visualized the impact of features on the model.
  - **SHAP Feature Dependence Plot:** Examined how features interact with each other.

- **Generating the Model on Selected Features**
  - **Evaluation:** Performance evaluation of the model using selected features.
  - **AUC Curve:** Analyzed ROC curve for the refined model.

### XGBoost - Extreme Gradient Boosting
- **Evaluate Predictions:** Analyzed model predictions. See [XGBoost](Final%20Project.ipynb#xgboost---extreme-gradient-boosting).
- **AUC Curve:** Evaluated model performance with ROC curve.
- **Grid Search Cross-Validation:** Optimized hyperp


## Additional Resources:  
[Poster - PDF](https://github.com/Shaked-g/FinalProject/blob/main/Additional%20Resources/Machine%20Learning%20Analysis%20of%20Enteral%20Feeding%20Intolerance%2C%2046.pdf "Poster")

[Literature research - Doc](https://github.com/Shaked-g/FinalProject/blob/main/Additional%20Resources/Literature%20Research.docx "Literature research")

[Final Project - Jupyter Notebook](https://github.com/Shaked-g/FinalProject/blob/3c5ed28b7e1c7f3ab40b9af4ae2849ec2299c676/Final%20Project.ipynb "Final Project.ipynb")


![Machine-Learning-Analysis-of-Enteral-Feeding-Intolerance-46 (3)](https://github.com/user-attachments/assets/aee06a4e-e186-40a1-b2de-b68a115e1b07)




