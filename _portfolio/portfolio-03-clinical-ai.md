---
title: "Clinical AI: Predicting the Duration of Oncology Clinical Trial"
collection: portfolio
link: "https://github.com/cynthiaxu04/predicting-clinicaltrials"
---

This project extracts novel duration-relevant features from unstructured clinical trial protocol text using regex and string pattern matching, assembles a dataset of 19,049 oncology studies from ClinicalTrials.gov spanning Phases 1–3, trains and benchmarks RandomForest, XGBoost, and LightGBM classifiers with scikit-learn to predict whether a trial will exceed the median duration, evaluates them on accuracy, precision, recall, F1, and ROC-AUC to beat the published state-of-the-art benchmark, and serves the trained model through a containerized web API that returns a predicted duration interval from user-supplied study parameters.
