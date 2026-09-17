
# Fetal Health CTG Classification

Machine learning model to classify fetal health from cardiotocography (CTG) recordings into three categories: Normal, Suspect, and Pathological.

## Overview

- **Data**: 2,126 CTG recordings with 21 physiological measurements
- **Model**: XGBoost gradient-boosted classifier
- **Performance**: ~91% Pathological recall on held-out test set
- **Purpose**: Triage support for clinical decision-making

## Features

- Exploratory analysis of CTG signal patterns
- Feature engineering and candidate evaluation
- Hyperparameter tuning with cross-validation
- Class imbalance handling comparison
- Threshold optimization for recall/false-alarm tradeoff

## Files

- `ctg_walkthrough.ipynb` - Complete pipeline walkthrough
- `fetal_health.csv` - Dataset
- `requirements.txt` - Dependencies
