# Final-project-FALL-2025
Wine-Type-Classification/
│
├── data/
│   ├── winequality-red.csv
│   ├── winequality-white.csv
│
├── notebooks/
│   ├── 1_preprocessing.ipynb
│   ├── 2_training_and_finetuning.ipynb
│
├── model/
│   └── logistic_model.pkl
│
├── results/
│   ├── confusion_matrix.png
│   ├── classification_report.txt
│
├── README.md
└── requirements.txt
# Wine Type Classification (Red vs White)

## Objective
To classify wine samples as red or white based on physicochemical properties using machine learning.

## Dataset
Two datasets are used:
- winequality-red.csv
- winequality-white.csv

A binary target variable `wine_type` is created to distinguish wine types.

## Preprocessing
- Merged red and white wine datasets
- Added target labels
- Feature scaling using StandardScaler
- Train-test split (80–20) with stratification

## Model Selection
Logistic Regression was chosen due to its effectiveness in binary classification and its support for hyperparameter fine-tuning.

## Training
The model is trained using iterative optimization (no epochs).

## Fine-Tuning
Hyperparameter `C` is optimized using GridSearchCV with cross-validation.

## Evaluation
- Accuracy
- Confusion Matrix
- Classification Report

## Submission
Project submitted via GitHub fork, ZIP upload, and pull request.
