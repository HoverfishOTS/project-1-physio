# Emotion Classification Using Physiological Signals

A 10-week summer research project for high school students.

**Title:** Emotion Classification Using Physiological Signals
**Research question:** Can physiological signals such as PPG, EDA, and heart rate predict emotional states using supervised machine learning?

## How to start

1. Open [`project_1_physiological.ipynb`](project_1_physiological.ipynb) -- or launch it directly in Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HoverfishOTS/project-1-physio/blob/main/project_1_physiological.ipynb)
2. Fill in every `TODO` cell from top to bottom.

Ask your instructor if stuck.

## 10-Week Plan

| Week | Tasks |
|------|-------|
| 1 | Learn basics of physiological signals: PPG, EDA, heart rate, stress response |
| 2 | Explore datasets. Define emotion labels. Load WESAD data |
| 3 | Clean signal data: remove missing values, normalize, segment time windows |
| 4 | Extract features: mean HR, HRV, EDA peaks, variance, min/max |
| 5 | Visualize features using plots and correlation heatmaps |
| 6 | Train baseline supervised models: logistic regression, decision tree, random forest |
| 7 | Evaluate using accuracy, precision, recall, F1 score, confusion matrix |
| 8 | Improve model with feature selection, scaling, hyperparameter tuning |
| 9 | Interpret results. Discuss ethical concerns, privacy, bias |
| 10 | Prepare final poster/paper and presentation |

## Datasets

- **WESAD (Wearable Stress and Affect Detection)** -- This dataset provides physiological data labeled for baseline, stress, and amusement states. [Kaggle Link](https://www.kaggle.com/datasets/orvile/wesad-wearable-stress-affect-detection-dataset)

## Key references

- NeuroKit2 Documentation: <https://neuropsychology.github.io/NeuroKit/>
- WESAD Dataset Paper: <https://dl.acm.org/doi/10.1145/3242969.3242985>