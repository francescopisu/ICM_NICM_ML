# Cine-Cardiac Magnetic Resonance to distinguish between ischemic and non-ischemic cardiomyopathies: a machine learning approach
This repository contains the code to reproduce the experiments of "Cine-Cardiac Magnetic Resonance to distinguish between ischemic and non-ischemic cardiomyopathies: a machine learning approach".

## Abstract

In this study, a Machine Learning (ML) model was developed to distinguish between Ischemic Cardiomyopathy (ICM) and Non-Ischemic Cardiomyopathy (NICM) using non-contrast Cardiovascular Magnetic Resonance (CMR) scans. The research involved 107 consecutive patients (49 ICM, 58 NICM) and employed an explainable tree-based gradient boosting additive model (GB-GAM) alongside traditional ML models for differentiation. Through extensive training and internal validation via cross-validation, the models achieved strong diagnostic accuracy and calibration. Crucial variables were identified for effectively discerning between ICM and NICM. The final model demonstrated a top area-under-curve (0.82) and lowest Brier score (0.19) following 10 repetitions of 10-fold cross-validation. Sensitivity at Youden’s index was 0.72, the highest among all models. The analysis underscored the significance of atrial and ventricular strain CMR parameters in identifying ICM patients. In conclusion, this research showcases the efficacy of an ML model that leverages multi-chamber myocardial strain and function from non-contrast CMR data to successfully differentiate between ICM and NICM with competitive diagnostic accuracy.

## Acknowledgements

* The code for comparing ROC AUCs using DeLong test is taken from the [Yandex School of Data Analysis github repository](https://github.com/yandexdataschool/roc_comparison).

