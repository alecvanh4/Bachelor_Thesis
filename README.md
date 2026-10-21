Coronary Heart Disease Prediction
Bachelor's thesis project exploring machine learning approaches for the early prediction of coronary heart disease using data from the Behavioral Risk Factor Surveillance System (BRFSS). The project covers data preprocessing, exploratory data analysis, and the comparison of classification models under different class-imbalance handling strategies.

Methods
-Data preprocessing: Variable selection, column renaming, handling of missing and invalid responses, and data imputation.
-Exploratory data analysis: Descriptive statistics, class distribution analysis, and visualization of variables such as age and BMI.
-Machine learning: Random Forest, XGBoost, and LightGBM classifiers.
-Class imbalance handling: Class weighting, ADASYN oversampling, and Borderline-SMOTE.
-Model evaluation: Classification reports, confusion matrices, and specificity.

Repository Structure
Preprocessing_1.ipynb — Selects relevant variables from the original survey data, renames columns, and handles invalid response codes.
Preprocessing_2.ipynb — Examines missing values, removes observations with missing values in selected variables, and applies imputation to remaining missing data.
Analysis.ipynb — Performs exploratory analysis, trains and evaluates classification models, and compares approaches to class imbalance.

Data: https://www.cdc.gov/brfss/annual_data/annual_2022.html

Technologies
Python, pandas, NumPy, scikit-learn, XGBoost, LightGBM, imbalanced-learn, Matplotlib, and Seaborn.
