# COMP41840 — AI for Health: Breast Cancer Classification

**University College Dublin | Group Project 2026**

## Project Overview
Multi-modal breast cancer classification using ultrasound images and clinical/genomic tabular data. Binary classification of benign vs malignant using imaging models, tabular models, and a late fusion of both.

## Dataset
- **Source:** [Kaggle — Multi-Modal Breast Cancer Dataset](https://www.kaggle.com/datasets/ajithdari/multi-modal-breast-cancer-dataset)
- 780 patients: benign (437), malignant (210), normal (133)
- Ultrasound images + segmentation masks
- Clinical history CSV (25 features)
- Molecular biomarker CSV (10 features)

## Project Structure
notebooks/
├── task1_eda.ipynb                  # Dataset exploration and analysis
├── task2_imaging_model.ipynb        # CNN imaging model (ResNet50)
├── task3_tabular_model.ipynb        # XGBoost clinical data model
├── task4_fusion_model.ipynb         # Late fusion model
└── task5_explainability.ipynb       # Grad-CAM + SHAP

## Results
| Model | Accuracy | AUC |
|-------|----------|-----|
| ResNet50 (Imaging) | 88% | 0.921 |
| XGBoost (Tabular) | TBD | TBD |
| Fusion Model | TBD | TBD |

## Team
- Axel Marchand
- Edward Mallia
- Aisling Wallace
