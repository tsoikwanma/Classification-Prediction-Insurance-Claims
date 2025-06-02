# Insurance Claim Prediction

Here contains the code and workflow for predicting insurance claim outcomes using various machine learning models, with a strong focus on handling imbalanced classification problems.

## Project-related Files

1. insurance.ipynb: full draft notebook containing all modeling steps, including,

- Exploratory Data Analysis (EDA)
- Preprocessing and transformation
- Comparison of multiple classification models (SVM RBF, SVM Polynomial, SVM Linear, KNN, and Logistic Regression Elastic Net)
- Evaluation using balanced accuracy
- Sampling strategies: SMOTE, SMOTETomek, Oversampling, Undersampling

2. insurance_final.ipynb: clean final notebook that,

- Loads the training data
- Trains the selected best model (SVM with linear kernel)
- Applies the model to the test set
- Saves predictions to a CSV file

3. classification.pdf: summary of the classification process, results, and justifications for model selection
