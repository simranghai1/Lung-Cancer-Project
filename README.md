# Lung-Cancer-Project

# Lung Cancer Risk Stratification (Classification)

## Business Problem
I built a machine learning model to predict elevated lung cancer risk to support early screening prioritization.

## Stakeholders
- Executive leadership (population health)
- Clinicians and care managers
- Patients
- Analytics team (monitoring and retraining)

## Data
Dataset: lung_cancer.csv  
Target: lung_cancer_risk (0/1)

## Approach (CRISP-DM)
1. Business understanding
2. Data understanding (EDA)
3. Data preparation (sklearn pipeline)
4. Modeling (3 algorithms + hyperparameter tuning + CV)
5. Evaluation (held-out test + threshold policy)
6. Business impact analysis + recommendations

## Results
Include:
- PR-AUC, ROC-AUC
- Recall@Top20% and Precision@Top20%
- Confusion matrix summary

## How to Run
download the dataset and the jupyter notebooks. upload the dataset into each notebook and run

## Limitations & Ethics
This model predicts lung cancer risk classification, not medical diagnosis. Predictions should be used to support clinical decision-making rather than replace professional judgment. Potential biases related to socioeconomic and demographic factors must be monitored to ensure equitable outcomes.

## Deployment & Next Steps
In production, the model would require ongoing performance monitoring, data drift detection, and periodic retraining. Future improvements could include longitudinal data and external validation.
