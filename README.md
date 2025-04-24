
# AI & ML Internship - Task 1

## Task: Data Cleaning & Preprocessing - Titanic Dataset

This project focuses on preparing raw data from the Titanic dataset for Machine Learning. The core operations include data cleaning, missing value handling, encoding, feature scaling, and outlier removal.

## Dataset:
Titanic dataset (downloaded from [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset))

## Tools Used:
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-Learn

## Steps Performed:
1. **Loaded Dataset**: Simulated Titanic data used (replace with actual dataset in practical usage).
2. **Handled Missing Values**: Filled missing 'Age' using median and 'Embarked' using mode.
3. **Categorical Encoding**: Used One-Hot Encoding for 'Sex' and 'Embarked'.
4. **Feature Scaling**: Standardized 'Age' and 'Fare' using StandardScaler.
5. **Outlier Removal**: Applied IQR method to clean outliers in the 'Fare' column.
6. **Saved Final Output**: Cleaned data ready for ML model input.

## Files Included:
- `Task1_Titanic_Preprocessing.ipynb`: Jupyter notebook with complete code and explanations.
- `titanic.csv`: Original dataset (to be added by user).
- `titanic_cleaned.csv`: Output dataset after preprocessing (to be generated from the notebook).

## Output:
A cleaned dataset that can now be used for training machine learning models.

## Author:
Hridiman Sarmah
