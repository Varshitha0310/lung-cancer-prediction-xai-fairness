# Lung Cancer Prediction using Machine Learning

##  Overview
This project focuses on predicting lung cancer using machine learning techniques
based on demographic, lifestyle, and clinical symptom data. In addition to
prediction accuracy, the study emphasizes Explainable AI (XAI) and fairness
evaluation to ensure reliable and unbiased model behavior.

##  Models Implemented
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest (Selected Model)
- AdaBoost
- Gradient Boosting
- Extra Trees Classifier

The Random Forest model was selected due to its balanced performance across
accuracy, precision, recall, and F1-score.

##  Dataset
- 309 patient records
- 16 clinical and demographic features
- Target variable: LUNG_CANCER (Yes / No)
- Age and Gender were used only for fairness evaluation

##  Explainable AI (XAI)
SHAP (SHapley Additive Explanations) was used to interpret model predictions and
analyze feature importance.

##  Fairness Evaluation
Fairness analysis was conducted across:
- Gender groups
- Age groups (Young, Middle-aged, Older)

No observable demographic bias was identified in the model’s predictions.

##  Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

##  Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- SHAP
- Matplotlib, Seaborn

##  Code
[View Jupyter Notebook](Lung_Cancer_Prediction.ipynb)

##  Dataset
[Lung Cancer Dataset](Lung_cancer_dataset.xls)

##  Report
[Project Report](Report.pdf)


##  Author
Varshitha Danduboina  
B.Tech Computer Science and Engineering (Final Year)
