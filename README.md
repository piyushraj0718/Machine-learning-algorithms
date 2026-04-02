# Machine Learning Algorithms – Practical Implementations

This repository is my personal collection of machine learning algorithm implementations that I built while learning ML. The main focus here is **understanding how algorithms actually work by implementing them and experimenting with datasets**, rather than writing theoretical notes.


#  Piyush Raj

  
Most notebooks contain:

* Data preprocessing
* Model training
* Hyperparameter tuning
* Performance evaluation
* Visualizations

This repo basically documents my hands-on ML learning journey.

---

## What this repository contains

The repository is organized by algorithm families and contains Jupyter notebooks for each implementation.

### Feature Engineering & ML Basics

Covers basic preprocessing and ML workflow steps like scaling, encoding, and feature preparation.

Folder:
`01.ml_FE`

---

## Supervised Learning Implementations

### Linear Regression

Location: `linear_regression/`

Implementations include:

* Simple Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Multicollinearity analysis
* Regularization (Lasso, Ridge, ElasticNet)

Focus was on understanding:

* How regression behaves with multiple features
* Effect of regularization
* Model evaluation metrics

---

### Logistic Regression

Location: `logistic_regression/`

Includes:

* Binary classification implementation
* Multiclass classification
* Hyperparameter tuning
* Decision boundary experiments

Focus was on practical classification workflow and model evaluation.

---

### Decision Trees

Location: `Decision_Tree/`

Includes:

* Decision Tree classifier
* Decision Tree regressor

Goal was to understand how tree depth and splits affect performance.

---

### KNN (K-Nearest Neighbors)

Location: `KNN/`

Includes:

* KNN Classifier
* KNN Regressor

Experiments focus on:

* Effect of K value
* Distance metrics
* Model sensitivity to scaling

---

### Naive Bayes

Location: `Naive Bayes/`

Includes:

* Gaussian Naive Bayes implementation

Focus was understanding probabilistic classification workflow.

---

### Support Vector Machines (SVM)

Location: `SVM/`

Includes:

* SVM Classifier
* SVM Regressor
* Kernel experiments

Focus was on:

* Kernel behavior
* Margin concepts through experimentation
* Model tuning

---

## Ensemble Learning

### Bagging

Location: `Bagging/`

Includes:

* Custom Bagging Classifier
* Custom Bagging Regressor
* Random Forest implementation
* Multi-model training experiments

Focus:
Understanding how combining models improves stability.

---

### Boosting & Stacking

Location: `Boosting & stacking/`

Includes:

* AdaBoost
* Gradient Boosting
* XGBoost
* CatBoost
* Stacking

Focus:
Understanding performance improvements from sequential learning.

---

## Unsupervised Learning

### PCA (Dimensionality Reduction)

Location: `PCA/`

Implementation of PCA for dimensionality reduction and visualization.

Focus:
Understanding variance capture and feature reduction.

---

### Clustering

Location: `USL_Clustering/`

Includes:

* K-Means
* Hierarchical Clustering
* DBSCAN

Focus:
Understanding how clustering behaves on different datasets.

---

## Anomaly Detection

Location: `Anomaly_Detection/`

Includes:

* Isolation Forest
* Local Outlier Factor
* DBSCAN based anomaly detection

Focus:
Detecting outliers and unusual patterns.

---

## Exploratory Data Analysis (EDA)

Location: `EDA/`

Contains multiple dataset analyses including:

* Google Play Store dataset
* HR dataset
* Healthcare dataset
* Student performance dataset

Focus:

* Data cleaning
* Feature relationships
* Visualization practice
* Dataset understanding before modeling

---

## Time Series

Location: `Time series/`

Includes:

* Time series analysis
* Forecasting experiments

Focus:
Understanding time dependent data behavior.

---

## Tools Used

Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
XGBoost
CatBoost

---

## How to run the notebooks

Clone the repo:

git clone https://github.com/piyushraj0718/Machine-learning-algorithms.git

Install dependencies:

pip install -r requirements.txt

Start Jupyter:

jupyter notebook

---

## Why I built this repo

I created this repository to:

* Practice ML by actually coding models
* Build intuition by experimenting
* Keep all implementations in one place
* Track my ML learning progress

This is more of a **learning workspace** than a polished library.

---

## Future additions (planned)

Things I may add later:

* Model comparison notebooks
* More datasets
* Feature engineering examples
* End-to-end ML projects
* Model deployment experiments

---

## Author

Piyush Raj

Machine Learning student interested in understanding algorithms from an implementation perspective and improving practical ML skills.

---

## Note

This repository is continuously updated as I learn new concepts and try new experiments.
