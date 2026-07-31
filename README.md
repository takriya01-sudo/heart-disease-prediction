Project Summary & Final Conclusions
1. Objective
The main goal of this project was to predict whether a patient is likely to have heart disease using clinical features from the Heart Disease UCI dataset.

2. Models Evaluated
Logistic Regression
Decision Tree Classifier
3. Model Performance Comparison
Logistic Regression: Accuracy = 82.61% | Recall = 83.49% | F1 Score = 0.8505 | AUC-ROC = 0.91
Decision Tree: Accuracy = 76.63% | Recall = 74.31% | F1 Score = 0.7902 | AUC-ROC = 0.77
4. Key Findings
Winner Model: Logistic Regression outperformed the Decision Tree across all metrics (Accuracy, Recall, and F1 Score).
ROC-AUC Score: Logistic Regression achieved an AUC score of 0.91, demonstrating excellent class separation capability.
Recall Focus: High Recall (83.49%) is critical in medical diagnosis to minimize False Negatives (avoiding missing a diseased patient).
5. Final Outcome
The fitted Logistic Regression Pipeline (best_pipeline) has been selected as the final production model for heart disease risk prediction.
