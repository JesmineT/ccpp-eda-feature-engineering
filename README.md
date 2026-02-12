# Combined Cycle Power Plant ML Workflow
This repository contains a Jupyter notebook for an end-to-end machine learning workflow using the Combined Cycle Power Plant dataset.

## Overview
- Loads and cleans real-world power plant data
- Performs exploratory data analysis (EDA) and outlier removal
- Engineers features (normalization, composite features)
- Encodes target variable for classification
- Handles class imbalance with under-sampling
- Selects features based on correlation analysis
- Trains and evaluates Decision Tree models on various feature sets
- Compares model performance and summarizes results

## How to Use
1. Download the Combined Cycle Power Plant dataset from [UCI](https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant).
2. Place the dataset in the working directory.
3. Run the notebook step by step to preprocess data, engineer features, and train models.
4. Review the output tables and plots for insights and model comparison.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

Install dependencies with:
```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
```

## Results
- The notebook compares multiple feature sets and preprocessing strategies.
- Feature selection and engineering improve model accuracy.
- Model performance is summarized in a comparison table.

---

**Author:** Jesmine Ting Zi Ching (2026)
