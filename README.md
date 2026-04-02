# Machine Learning Algorithms – Practical Implementations

# PIYUSH RAJ 


This repository is a structured collection of machine learning algorithms that I implemented while learning ML through hands-on practice. The goal of this project is not theory notes, but to understand how models behave by actually building, testing, and experimenting with them on datasets.

Instead of keeping scattered notebooks, I organized everything into a proper learning flow covering EDA → feature engineering → supervised learning → ensemble methods → unsupervised learning → anomaly detection → time series.

This repository basically represents my practical ML learning journey.

---

## Repository Structure

The repository is organized in the order someone typically learns and applies machine learning:

```
Machine-Learning-Algorithms

01_EDA
02_Feature_Engineering
03_Linear_Regression
04_Logistic_Regression
05_Decision_Tree
06_SVM
07_Bagging
08_Naive_Bayes
09_Boosting_Stacking
10_KNN
11_PCA
12_Clustering
13_Anomaly_Detection
14_Time_Series

README.md
requirements.txt
```

---

## What each section contains

### 01 – Exploratory Data Analysis (EDA)

Practice notebooks focused on understanding datasets before modeling.

Work includes:

* Data cleaning
* Handling missing values
* Feature relationships
* Visualization
* Dataset exploration

Datasets used include:

* Google Play Store data
* HR analytics data
* Healthcare dataset
* Student performance dataset
* Travel dataset

---

### 02 – Feature Engineering

Practical preprocessing techniques used before training models:

Topics covered:

* Missing value handling
* Imbalanced data handling
* Data interpolation
* Outlier detection
* Feature scaling
* Encoding categorical variables

Focus was on building strong preprocessing intuition.

---

## Supervised Learning Implementations

### 03 – Linear Regression

Regression experiments including:

* Simple Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Multicollinearity analysis
* Regularization techniques:

  * Ridge
  * Lasso
  * ElasticNet

Main focus:
Understanding how regression changes with features and regularization.

---

### 04 – Logistic Regression

Classification experiments including:

* Binary classification
* Multiclass classification
* Hyperparameter tuning
* Decision boundary exploration

Focus:
Understanding classification workflow and evaluation.

---

### 05 – Decision Trees

Includes:

* Decision Tree classifier
* Decision Tree regressor

Focus:
Understanding how splits, depth, and parameters affect model behavior.

---

### 06 – Support Vector Machines (SVM)

Includes:

* SVM classification
* SVM regression
* Kernel experiments

Focus:
Understanding kernel effects and margin behavior through experimentation.

---

### 10 – K Nearest Neighbors (KNN)

Includes:

* KNN classifier
* KNN regressor

Experiments include:

* Choosing optimal K
* Distance metrics
* Effect of scaling

---

### 08 – Naive Bayes

Includes:

* Gaussian Naive Bayes implementation

Focus:
Understanding probabilistic classification and feature independence assumptions.

---

## Ensemble Learning

### 07 – Bagging

Includes:

* Custom Bagging Classifier
* Custom Bagging Regressor
* Random Forest experiments
* Multi-model training

Focus:
Understanding how combining models reduces variance.

---

### 09 – Boosting & Stacking

Includes implementations of:

* AdaBoost
* Gradient Boosting
* XGBoost
* CatBoost
* Stacking

Focus:
Understanding how sequential learning improves performance.

---

## Unsupervised Learning

### 11 – PCA

Dimensionality reduction experiments.

Focus:

* Variance capture
* Feature reduction
* Visualization

---

### 12 – Clustering

Includes:

* K Means
* Hierarchical clustering
* DBSCAN

Focus:
Understanding how clustering behaves on different datasets.

---

## 13 – Anomaly Detection

Includes:

* Isolation Forest
* Local Outlier Factor
* DBSCAN based anomaly detection

Focus:
Detecting unusual observations and outliers.

---

## 14 – Time Series

Includes:

* Time series analysis
* Basic forecasting experiments

Focus:
Understanding time dependent data patterns.

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
Jupyter Notebook

---

## How to run the notebooks

Clone the repository:

```
git clone https://github.com/piyushraj0718/Machine-learning-algorithms.git
```

Install dependencies:

```
pip install -r requirements.txt
```

Run Jupyter:

```
jupyter notebook
```

---

## Why I built this repository

I built this repo mainly to:

* Practice ML through implementation instead of passive learning
* Build intuition about how algorithms behave
* Keep all experiments organized
* Track my progress while learning ML
* Create a structured reference for revision

This repository is more of a **learning workspace** than a finished ML product.

---

## Future improvements

Things I plan to add:

* End-to-end ML projects
* Model comparison notebooks
* Feature engineering case studies
* Model deployment experiments
* Pipeline based workflows

---

## Author

Piyush Raj

Machine Learning student focused on learning algorithms through implementation and experimentation.

---

## Note

This repository is continuously updated as I learn new topics and improve my understanding of machine learning.
