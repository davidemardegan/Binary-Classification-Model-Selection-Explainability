# Binary Classification: Model Selection & Explainability

Individual university project completed for **Mathematical Modelling for Machine Learning** at Bocconi University (2026).

**Project files:** [Jupyter notebook](./MLpersonalproject_mardegan.ipynb) · [HTML report](./MLpersonalproject_mardegan.html) · [PDF report](./MLpersonalproject_mardegan.pdf)

## Overview

This project develops and evaluates a complete machine-learning workflow for **binary classification** on mixed numerical and categorical tabular data.

The emphasis is not only on predictive performance, but also on understanding how modelling choices affect the result and how model behaviour can be interpreted.

## Methods

The project includes:

- leakage-safe preprocessing pipelines
- exploratory feature analysis
- mutual information and correlation analysis
- PCA and t-SNE
- Logistic Regression and linear SVM baselines
- polynomial feature interactions
- Random Forest and CatBoost
- hyperparameter tuning with cross-validation
- SHAP-based feature interpretation

## Result

Polynomial Logistic Regression achieved the strongest cross-validated performance, with a **balanced accuracy of approximately 0.829**, improving on the standard linear baselines.

## LLM Audit

Dedicated **LLM Audit** sections compare selected methodological and modelling choices with suggestions from ChatGPT 5.5, critically assessing where the recommendations aligned with or differed from the final approach.

The purpose is not to outsource the analysis, but to make the reasoning process explicit and evaluate LLM suggestions as an additional source of methodological feedback.

## Technologies

Python · pandas · NumPy · scikit-learn · CatBoost · SHAP · machine learning · model selection

## Course context

**Mathematical Modelling for Machine Learning — Bocconi University, 2026**
