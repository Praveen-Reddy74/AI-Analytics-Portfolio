## Methodology
The project follows a structured machine learning pipeline:

1. **Data Preprocessing**
   - Handling missing values
   - Feature scaling
   - Train-test split

2. **Class Imbalance Handling**
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)** to improve minority class representation

3. **Model Training**
   - Baseline and ensemble classifiers were trained and compared

4. **Hyperparameter Optimization**
   - Grid Search Cross Validation
   - Randomized Search Cross Validation

5. **Model Evaluation**
   - Accuracy
   - F1 Score
   - Confusion Matrix
   - K-Fold Cross Validation

---

## Models Implemented
The following models were evaluated:

- Logistic Regression (Balanced)
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Extra Trees Classifier
- Gradient Boosting
- AdaBoost
- Voting Classifier

Each model was tested **before and after applying SMOTE** to analyze the impact of imbalance correction.

---

## Evaluation Metrics
To ensure reliable and clinically meaningful results, the following metrics were used:

- Mean Cross-Validation Accuracy
- Standard Deviation of CV Accuracy
- Train Accuracy vs Test Accuracy
- Precision, Recall, and F1 Score
- Confusion Matrix

Special emphasis was placed on **F1-score**, as accuracy alone can be misleading for imbalanced datasets.

---
