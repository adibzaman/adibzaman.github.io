---
title: "Classification of short single-lead electrocardiograms (ECGs) for atrial fibrillation detection using piecewise linear spline and XGBoost"
collection: publications
permalink: /publication/2018-10-24-Classification-short
excerpt: ''
date: 2018-10-24
venue: 'Physiological measurement'
paperurl: 'https://iopscience.iop.org/article/10.1088/1361-6579/aadf0f'

---

Objective: Detection of atrial fibrillation is important for risk stratification of stroke. We developed a novel methodology 
to classify electrocardiograms (ECGs) to normal, atrial fibrillation and other cardiac dysrhythmias as defined by the 
PhysioNet Challenge 2017. Approach: More specifically, we used piecewise linear splines for the feature selection and a 
gradient boosting algorithm for the classifier. In the algorithm, the ECG waveform is fitted by a piecewise linear spline, 
and morphological features relating to the piecewise linear spline coefficients are extracted. XGBoost is used to classify 
the morphological coefficients and heart rate variability features. Main results: The performance of the algorithm was 
evaluated by the PhysioNet Challenge database (3658 ECGs classified by experts). Our algorithm achieved an average F1 
score of 81% for a 10-fold cross-validation and also achieved 81% for F1 score on the independent testing set. This score 
is similar to the top 9th score (81%) in the official phase of the PhysioNet Challenge 2017. Significance: Our algorithm 
presents a good performance on multi-label short ECG classification with selected morphological features