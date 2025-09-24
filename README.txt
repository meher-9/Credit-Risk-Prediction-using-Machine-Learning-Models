
README: Credit Risk Prediction Project

-> Project Overview
This project predicts whether a customer will be risky on their credit card payment next month based on their credit usage history and demographic data.

-> How to Run the Notebook

Step 1: Prepare Your Environment
Ensure you have Python 3.7+ and Jupyter Notebook or Google Colab.

Step 2: Install Required Libraries
Use pip to install dependencies:
pip install pandas numpy matplotlib scikit-learn

Step 3: Run the Notebook
- Open commentedcode.py in Jupyter or Colab.
- Ensure Credit Risk Prediction.csv is in the same directory or uploaded to Colab.
- Run all cells sequentially.

You will see printed evaluation metrics and plotted visualizations for each model.

-> Dependencies and Libraries
- pandas: Data manipulation
- numpy: Numerical operations
- matplotlib: Plotting graphs
- scikit-learn: Machine learning pipeline and models
  - train_test_split, StandardScaler, OneHotEncoder
  - LogisticRegression, RandomForestClassifier, SVC
  - Pipeline, ColumnTransformer
  - accuracy_score, precision_score, recall_score, f1_score, roc_auc_score
  - ConfusionMatrixDisplay, RocCurveDisplay

-> Output and Results
- The notebook trains 3 models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)

- It evaluates each model using:
  - Accuracy, Precision, Recall, F1 Score, ROC AUC
  - Confusion Matrix and ROC Curve visualizations

-> Files Included
- commentedcode.py: Full code with comments
- Credit Risk Prediction.csv: Dataset
- credit_risk_report.pdf: Final project report
- classification_report.txt: Summary of model evaluation
- README.txt: This guide

