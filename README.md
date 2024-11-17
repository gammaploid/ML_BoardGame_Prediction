# Machine Learning Board Game Analysis and Prediction 

This repository contains a machine learning analysis of a dataset from Ludii board games [Ludii.games](https://ludii.games/) general game system, focusing on predicting board game attributes. 
The project includes regression and classification tasks, along with preprocessing, feature engineering, and evaluation.

## Objectives
- Predict numerical attributes like `OriginYear` and `UCT`.
- Classify categorical labels like `Category`, `Region`, and `BestAgent`.

## Key Techniques
- PCA for dimensionality reduction
- Outlier detection using K-Means clustering
- Model training with Random Forest and Stacking regressors/classifiers
- Hyperparameter tuning and cross-validation

## Prerequisites

- **Python 3.x**
- **Pip**: Python package installer, or alternatively Conda.
- **Libraries**:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - Jupyter Notebook 
- **GameData.csv**: Sourced from [Ludii.games](https://ludii.games/). Clone the repository to access the dataset.
  
You can install the required libraries using pip.

## License
This project is licensed under the MIT License.
