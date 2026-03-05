# Assignment 5 SciKit
# Breast Cancer Classification (scikit-learn) — 3 Models + Best Model Selection

## Purpose
This project demonstrates **machine learning classification** using Python and **scikit-learn** on real-world medical diagnostic data. It uses the built-in **Breast Cancer Wisconsin** dataset to train and evaluate **three different classification models** and determine which model performs best using standard train/validation/test splitting practices.

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

## How to Run
This project is implemented in a **Jupyter Notebook**.

1. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn matplotlib
