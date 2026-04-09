# Interpretable ML Evaluation

This project focuses on the quantitative evaluation of explainability methods for machine learning models using synthetic tabular data with known ground truth feature importance.The goal of this project is to analyze how well different explanation methods capture the true behavior of a modeld.

The following explanation methods are evaluated:

- **Gradient-based explanations**
- **LIME (Local Interpretable Model-agnostic Explanations)**
- **SHAP (SHapley Additive exPlanations)**

##  Dataset
The dataset is synthetically generated with conditional logic and noise features with no real influence

##  Model
A simple feedforward neural network (MLP) implemented in PyTorch is trained on the dataset.

## Structure

- `notebook.ipynb` – main Google Colab notebook with code and experiments  
- `report.pdf` – written report (currently in Slovak)  
