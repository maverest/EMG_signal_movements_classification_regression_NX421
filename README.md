# EMG Signal Processing - Movement Classification & Joint-Angle Regression NX-421 Project 2

This repository contains the code and report of our work on the NX-421 mini-project 2.

---
We perform a full pipeline—from raw electromyography (EMG) preprocessing to machine learning models for classifying hand/wrist movements and predicting joint angles using the NinaPro database. The work is divided into two main tasks:

1. **Movement Classification**  
   - Preprocess EMG signals (filtering, envelope extraction, segmentation)  
   - Extract time- and frequency-domain features  
   - Train and optimize support-vector classifiers (SVC) via grid search  
   - Evaluate performance using accuracy, confusion matrices and F₁ scores

2. **Joint-Angle Regression**  
   - Process synchronized EMG and kinematic data  
   - Select informative features with mutual information and PCA  
   - Use multi-output support-vector regression (SVR)  
   - Tune hyperparameters and assess with RMSE and MAE metrics

---
The code and environment.yml are provided for reproducibility. See the [report](./report.pdf) for details about results and analysis.


