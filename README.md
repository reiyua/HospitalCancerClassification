# Hospital Cancer Risk Classification

A simple machine learning project that classifies patient cancer risk levels using demographic and health history data.

## Overview

This project was created as part of an ICT and Machine Learning assessment scenario for TAFE NSW.

The goal was to build and evaluate a neural network model capable of classifying patients into:

- High Risk
- Medium Risk
- Low Risk

The model helps healthcare professionals identify patients who may require closer monitoring or early intervention.

---

## Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy

---

## Machine Learning Model

This project uses Scikit-learn's:

- `MLPClassifier`

The model was trained and evaluated using prepared healthcare data.

---

## Dataset Preparation

### Age Categories

Patient ages were grouped into:

- 0–14
- 15–24
- 25–34
- 35–44
- 45–54
- 55–64
- 65–74
- 75–84
- 85+

### Data Split

The dataset was split into:

- 70% Training
- 15% Validation
- 15% Testing

---

## Running the Notebook

Clone the repository:

```bash
git clone https://github.com/reiyua/HospitalCancerClassification.git

```
You can also run it online:

## Run in Google Colab

[![Run in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/reiyua/HospitalCancerClassification/blob/main/HospitalCancerClassification.ipynb)

## Run in mybinder.org
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/reiyua/HospitalCancerClassification/HEAD)
