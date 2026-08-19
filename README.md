Readme · MD
Stroke Prediction - Model Comparison

A machine learning project that predicts stroke risk from patient health data, comparing multiple classification models to identify the most accurate approach.

Dataset

healthcare-dataset-stroke-data.csv - patient records including age, hypertension, heart disease, average glucose level, BMI, smoking status, and whether the patient had a stroke.

The dataset was balanced (equal stroke / no-stroke cases) before training to avoid bias toward the majority class.

Models compared
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Results
Model	Accuracy	Recall (Catching Strokes)	F1-Score
Logistic Regression	0.81	0.82	0.81
Decision Tree	0.74	0.70	0.73
Random Forest	0.81	0.80	0.81
KNN	0.53	0.54	0.53

Logistic Regression and Random Forest performed best overall. KNN performed poorly even after tuning for the best k value.

How to run
Make sure healthcare-dataset-stroke-data.csv is in the same folder as the notebook.
Install the required packages: pandas, numpy, scikit-learn, matplotlib, seaborn, openpyxl.
Open Strokepredict.ipynb and run all cells.
