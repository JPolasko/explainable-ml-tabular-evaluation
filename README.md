# Interpretable ML Evaluation

This project focuses on the quantitative evaluation of explainability methods for machine learning models using synthetic tabular data with known ground truth feature importance.The goal of this project is to analyze how well different explanation methods capture the true behavior of a modeld.

The following explanation methods are used:

- **Gradient-based explanations**
- **LIME (Local Interpretable Model-agnostic Explanations)**
- **SHAP (SHapley Additive exPlanations)**

##  Dataset
The dataset is synthetically generated with conditional logic and noise features.

##  Model
A simple feedforward neural network implemented in PyTorch with accuracy 88% on test data.

## Structure

- `notebook.ipynb` – main Google Colab notebook with code and experiments  
- `report.pdf` – written report (currently in Slovak)  
