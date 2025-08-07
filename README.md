# Epitope-Classification
A deep learning project for epitope pattern prediction from highly imbalanced data using XGBoost and SMOTE.
# Epitope Pattern Prediction using Deep Learning

This project aims to predict rare epitope patterns from a highly imbalanced biomedical dataset, using preprocessing, class rebalancing, and model selection techniques.

## 🧪 Problem Statement
Predicting a rare epitope classification (Class 1) from a massive dataset with 45,000 samples and 1635 features. The data exhibits severe class imbalance and potential overfitting risks.

## 🧠 Techniques Used
- Exploratory Data Analysis (EDA)
- PCA & Feature Selection (`SelectKBest`)
- SMOTE for class balancing
- Model evaluation using GroupKFold
- Models: RandomForest, XGBoost

## 🏆 Best Results
- `XGBoost + SelectKBest (200 features)`
- Balanced Accuracy: **0.70**
- Recall for minority class: **0.40**

## 📁 Files
- `Joseph_Caroline_AM41UD_Notebook.ipynb`: Full implementation
- `Joseph_Caroline_AM41UD_Report.docx`: Summary report with analysis

## 🔍 Limitations
- Limited by personal machine’s computation power.
- Could not perform deeper hyperparameter tuning or try BORUTA feature selection.

## 🚀 Future Work
- Try model ensembling and optimal thresholding
- Implement on more powerful hardware
- Explore real-world application in biomedical research

