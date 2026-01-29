# Predictive-Analytics-for-Neurological-Diseases

### Early Detection & Prognosis of Alzheimer’s Disease Using Predictive Analytics

This project leverages longitudinal patient data from the Alzheimer’s Disease Neuroimaging Initiative (ADNI) to predict progression from Mild Cognitive Impairment (MCI) to Alzheimer’s Disease (AD). Using predictive analytics and machine learning, the study aims to provide early warnings and actionable insights for patient monitoring.

## Project Overview

Objective: Apply predictive models to classify patients, forecast AD progression, and identify early warning signals of cognitive decline.

Scope: Focus on understanding temporal patterns in biomarkers and cognitive assessments to predict conversion from MCI to AD.

## Tools & Techniques

- Languages & Libraries: Python, Pandas, Scikit-learn, TensorFlow/Keras

- Models: LightGBM, Random Forest, RNN, LSTM

- Evaluation Metrics: Recall, Precision, F1 Score, ROC-AUC

- Explainability: SHAP, LIME for feature importance

- Framework: CRISP-DM methodology

## Key Findings

- Best Model: LSTM achieved the highest predictive performance (Recall: 83.7%, F1: 84.2%).

- Explainability: Cognitive and biomarker features identified as most influential for progression.

- Alert Framework: Flags sudden cognitive decline, complementing clinical monitoring.

## Why This Matters

Early detection of Alzheimer’s disease allows for timely interventions and better patient outcomes. This project demonstrates how predictive analytics and explainable AI can support clinical decision-making and enhance longitudinal patient monitoring.

## Repository Contents

- data/ – Processed ADNI datasets (note: original data subject to ADNI access policies)

- Dissertation/ – Jupyter notebooks with data exploration, modelling, and evaluation

- src/ – Scripts for preprocessing, model training, and evaluation

- requirements.txt – Required Python packages for reproducing results.

## How to Use

- Clone this repository:
git clone https://github.com/YourUsername/AD-Predictive-Analytics.git


- Install dependencies:
pip install -r requirements.txt


- Run the notebooks or scripts to reproduce preprocessing, training, and evaluation results.

## License

This project is for research and portfolio purposes, data must not be reused unless sourced for from Alzheimer’s Disease Neuroimaging Initiative (ADNI).

