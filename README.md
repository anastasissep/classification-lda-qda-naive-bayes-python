# Pattern Recognition — Classification (LDA, QDA, Naive Bayes)

This repository contains a **Jupyter Notebook** for a supervised classification task in the context of **Pattern Recognition**.  
The notebook includes data exploration, preprocessing, model training, and evaluation using classic statistical classifiers.

## Overview
The workflow includes:
- Exploratory Data Analysis (EDA) using descriptive statistics and boxplots
- Handling missing values (missing entries replaced with the **mean of the corresponding column**)
- Training and comparing multiple classifiers:
  - **LDA** (Linear Discriminant Analysis)
  - **QDA** (Quadratic Discriminant Analysis)
  - **Naive Bayes**

## Repository contents
- `project_classification_pattern_recognition.ipynb` — main notebook (analysis + code + results)
- `project_report_classification_pattern_recognition.docx` — project report (documentation)

## How to run
### Requirements
- Python 3.x (Anaconda recommended)
- Jupyter Notebook / JupyterLab

### Run locally
1. Open a terminal in the repository folder
2. Start Jupyter:
```bash```
jupyter notebook
Open project_classification_pattern_recognition.ipynb and run all cells.

Notes on the models

LDA: Performs well when the feature–target relationship is approximately linear.

QDA: Can model more complex relationships, but may overfit on smaller datasets.

Naive Bayes: Fast and efficient, but assumes feature independence, which often does not hold.

Results

All evaluation results (metrics/plots) are available inside the notebook.

Author

anastasissep
