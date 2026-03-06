# Assignment 5 SciKit
# Breast Cancer Classification (scikit learn) — 3 Models + Best Model Selection

## Purpose
This project demonstrates **machine learning classification** using Python and **scikit learn** on real world medical diagnostic data. It uses the built-in **Breast Cancer ** dataset to train and evaluate **three different classification models** and determine which model performs best using standard train/validation/test splitting practices.

Early detection has played a major role in improving breast cancer outcomes, and classification models like these can help identify patterns that distinguish **malignant** vs **benign** cases.

---

## Dataset
- **Source:** `sklearn.datasets.load_breast_cancer()`
- **Samples:** 569
- **Features:** 30 numeric features derived from digitized images of breast mass cell nuclei
- **Target classes:**
  - `0` = Malignant  
  - `1` = Benign  

---

## Results
- Accuracy: 0.9736842105263158
- Precision: 0.9726027397260274
- Recall: 0.9861111111111112
- F1 Score: 0.9793103448275862
- ROC-AUC: 0.9957010582010581
## The confusion matrix produced the values below
- True Malignant Predicted Malignant: 40
- True Malignant Predicted Benign: 2
- True Benign Predicted Malignant: 1
- True Benign Predicted Benign: 71

# Out of 114 predictions, only three were incorrect. This demonstrates that the model is highly accurate and capable of correctly classifying the vast majority of cases

## Findings / Conclusion
- The best model has a very high ability to classify tumors accurately based on all of the performance metrics measured in this evaluation. The extremely high ROC-AUC score of 0.9957 shows that the model performs extraordinarily well when trying to differentiate between malignant tumors and benign tumors.

- The recall score of 0.9861 demonstrates that the model was able to identify almost all of the positive cases, making it critical for models that utilize medical diagnostic applications because if you miss identifying the malignant tumors, the result can be disastrous.

- In addition, only three of the total number of samples (114) were predicted incorrectly by the model (as seen in the confusion matrix), which means that all but three of the test samples were classified correctly. With an F1 score of 0.9793, the model has very good precision and recall, suggesting that it performs well in correctly identifying cases of cancer, while minimizing the number of false-positive predictions.
- In conclusion, the results described above indicate that the model generalizes well to new data and produces useful predictions for breast cancer classification
