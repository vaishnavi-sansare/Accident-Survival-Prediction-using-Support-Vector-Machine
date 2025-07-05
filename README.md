# Accident Survival Prediction using SVM

This project demonstrates how to use a Support Vector Machine (SVM) classifier to predict accident survival outcomes based on various factors. The dataset `Accident_survival.csv` contains several parameters that could influence survival, and the `survived` column (1 - survived, 0 - not survived) is used as the target.

## Dataset
- `Accident_survival.csv` — the dataset used for training and testing.
- Target column: **`survived`**

## Approach
- Data preprocessing and splitting into training/testing sets.
- Designed and trained Support Vector Classifiers with various kernels:
  - Linear Kernel
  - Polynomial Kernel
  - RBF Kernel
  - Sigmoid Kernel
- Evaluated the classifiers using metrics like accuracy score, confusion matrix, and classification report.

## Technologies Used
- Python
- scikit-learn
- pandas, numpy, matplotlib

### Results
The performance of different SVM kernels was compared to find the best fit for the accident survival prediction problem. The results highlight how kernel choice can significantly affect classification accuracy.

