# Machine Learning Metrics

This document outlines typical metrics used in machine learning to evaluate the performance of a model.


## 📊 Classification

These task metrics are often derived from the components of a confusion matrix which provides a summary of the prediction results on a classification problem. 
The number of correct and incorrect predictions are summarized with count values and broken down by each class.

### Confusion Matrix

For a binary classification problem, the confusion matrix has four components:

*   **True Positives (TP):** The model correctly predicted the positive class.
*   **True Negatives (TN):** The model correctly predicted the negative class.
*   **False Positives (FP):** The model incorrectly predicted the positive class (a "Type I error").
*   **False Negatives (FN):** The model incorrectly predicted the negative class (a "Type II error").

| Metric | Formula |
| :--- | :--- |
| **Accuracy** | $$\frac{TP + TN}{TP + TN + FP + FN}$$ |
| **Precision** | $$\frac{TP}{TP + FP}$$ |
| **Recall (Sensitivity)** | $$\frac{TP}{TP + FN}$$ |
| **Specificity** | $$\frac{TN}{TN + FP}$$ |
| **F1-Score** | $$2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}$$ |
| **Balanced Accuracy** | $$\frac{\text{Sensitivity} + \text{Specificity}}{2}$$ |
| **Intersection over Union (IoU)** | $$\frac{TP}{TP + FP + FN}$$ |

---
