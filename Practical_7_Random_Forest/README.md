# Practical Work 7 — Random Forest

## Dataset

**Dry Bean Dataset**

The dataset contains 13,611 instances, 16 numerical features, and 7 classes of dry beans.

## Objective

The objective of this practical work is to build and optimize a Random Forest classification model and analyze feature importance.

## Tasks

1. Explore and prepare the dataset.
2. Train a Decision Tree classifier.
3. Train a Random Forest classifier with default parameters.
4. Tune Random Forest hyperparameters using GridSearchCV.
5. Compare model performance using Accuracy and Macro F1-score.
6. Analyze feature importance.
7. Evaluate model performance after removing less important features.
8. Draw conclusions based on experimental results.

## Hyperparameters

The following parameters were tuned:

- `n_estimators`
- `max_depth`
- `min_samples_leaf`

Three-fold cross-validation and Macro F1-score were used for model selection.

## Project Structure

```text
Practical_7_Random_Forest/
│
├── data/
│   └── DryBeanDataset/
│       ├── Dry_Bean_Dataset.arff
│       └── Dry_Bean_Dataset.xlsx
│
├── notebooks/
│   └── random_forest.ipynb
│
├── README.md
└── model_comparison.csv
```

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Dataset Source

UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/602/dry+bean+dataset

## Results

The experimental results and conclusions are presented in the Jupyter Notebook.