
---

## Results Summary
- Ensemble models consistently outperformed single classifiers.
- **Extra Trees and Random Forest with SMOTE** achieved the best balance between accuracy and generalization.
- SMOTE significantly improved minority-class detection and F1 scores.
- Hyperparameter tuning further enhanced model stability and reduced overfitting.
- Cross-validation confirmed consistent performance across different data splits.

---

## Results

### Hyperparameter Tuning (Grid Search)
![Grid Search Results](./GridSearch_Tuning_Results_CHD_Classification.png)

Grid Search was used to optimize AdaBoost hyperparameters, identifying the best configuration based on cross-validated accuracy. The optimal model achieved a strong balance between bias and variance.

---

## Model Performance After SMOTE (K-Fold Cross Validation)

![K-Fold CV After SMOTE](./K-Fold%20CV%20Accuracy_After_SMOTE_CHD.png)

After applying SMOTE, ensemble models showed improved cross-validation accuracy, reduced variance, and better minority-class detection.

---

## Model Performance Before SMOTE (K-Fold Cross Validation)

![K-Fold CV Before SMOTE](./K-Fold%20CV%_20Accuracy_Before_SMOTE_CHD.png)

Before SMOTE, models exhibited higher apparent accuracy but significantly weaker F1 sco

---

### Randomized Search Cross-Validation Results
![Randomized CV Results](./Randomized_CV_Results_CHD_Patients_Classification.png)

Randomized Search CV further evaluated multiple model configurations efficiently, confirming the superiority of ensemble methods when combined with imbalance-handling techniques.
---
