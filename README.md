# ML-Foundations

The core repository for classical machine learning algorithms, statistical modeling, and production-grade data pipelines.

## Overview

While Deep Learning and GenAI handle unstructured data (text, images), classical Machine Learning remains the undisputed industry standard for tabular data, risk modeling, and structured prediction tasks.

This repository serves as both an archive for foundational statistical projects and an active proving ground for advanced, production-level classical ML techniques.

## Archive & Core Implementations

_(Moved from previous directories)_

- Principal Component Analysis (PCA) and dimensionality reduction.
- Support Vector Machines (SVM) and kernel tricks.
- Random Forests and ensemble learning baselines.
- Linear/Logistic Regression models built from first principles.

## Future Roadmap: Production ML

The next phase of this workspace focuses on shifting from "Jupyter Notebook experiments" to robust, automated, production-ready machine learning architectures.

1. **Automated Hyperparameter Tuning:**
   - Integrate `Optuna` frameworks into standard scikit-learn pipelines.
   - Move away from grid search to Bayesian optimization for faster convergence.
2. **Advanced Tree Methods:**
   - Implement `XGBoost` and `LightGBM` models with custom, business-logic-driven loss functions (e.g., asymmetric penalty for false positives in fraud detection).
3. **Model Interpretability (XAI):**
   - Implement `SHAP` (SHapley Additive exPlanations) and `LIME` to reverse-engineer tree models and explicitly prove _why_ a model made a specific prediction.
4. **Custom Sklearn Pipelines:**
   - Write custom Python classes inheriting from `BaseEstimator` and `TransformerMixin` to encapsulate messy data cleaning steps (imputation, scaling, one-hot encoding) into a single, deployable `.pkl` pipeline object.
