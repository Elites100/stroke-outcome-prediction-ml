# Stroke Outcome Prediction Using Machine Learning

## Overview
This project uses machine learning to classify recorded stroke outcomes based on patient health characteristics. It compares Logistic Regression and Random Forest models using Python and Scikit-learn.

## Technologies
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Google Colab

## Dataset
The project uses the [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) from Kaggle.

## Project Workflow
- Performed exploratory data analysis (EDA) to examine patient characteristics and stroke outcomes.
- Preprocessed data by handling missing values, encoding categorical variables, and addressing class imbalance.
- Trained and compared Logistic Regression and Random Forest classification models.
- Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices.

## Model Results

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 74.56% | 94.91% |
| Precision | 13.79% | 0.00% |
| Recall | 80.00% | 0.00% |
| F1-score | 23.53% | 0.00% |

Logistic Regression identified 40 of 50 stroke-positive cases in the test set, while Random Forest failed to identify any positive cases. This demonstrates why accuracy alone can be misleading when working with imbalanced datasets.

## Limitations
This project is an educational machine learning experiment. The models are not intended for medical diagnosis, clinical screening, or real-world medical decisions.

## Future Improvements
- Experiment with additional classification algorithms.
- Explore feature importance.
- Test different classification thresholds.
- Evaluate performance on additional datasets.
