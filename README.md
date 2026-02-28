# ML-Notebook

#### *Karma of Humans is A.I.*

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-ff6f00?logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive, hands-on machine learning curriculum — from NumPy basics to neural networks. Each module contains Jupyter notebooks with **from-scratch implementations** alongside scikit-learn equivalents, applied to real-world datasets.

```bash
git clone https://github.com/the-mrinal/ML-Notebook.git
```

---

## Curriculum

### Foundations

| Module | Topic | Notebooks |
|--------|-------|-----------|
| 02 | NumPy Arrays | Array operations, histograms, visualization |
| 03 | Graphs | Plotting fundamentals |
| 04 | Plotting Graphs | Advanced matplotlib techniques |
| 05 | Intro to Datasets | Exploratory analysis on the Titanic dataset |

### Regression

| Module | Topic | Highlights |
|--------|-------|------------|
| 06 | Linear Regression | From-scratch `fit()` & `predict()`, R² score, cost functions |
| 07 | Multivariable Regression | Multiple features, gradient descent (iterative improvements) |
| 08 | Combined Cycle Power Plant | Feature-based regression with gradient descent |

### Classification

| Module | Topic | Highlights |
|--------|-------|------------|
| 09 | Logistic Regression | Binary classification, Titanic survival prediction |
| 10 | Confusion Metrics | Precision, recall, F1-score, classification reports |
| 11 | Decision Tree | sklearn + graphviz visualization, Iris & Titanic datasets |
| 15 | Naive Bayes | From-scratch with Laplace smoothing, Iris dataset |
| 16 | KNN | From-scratch + sklearn, cross-validation, hyperparameter tuning |
| 18 | SVM | Linear SVM, decision boundary visualization |

### Feature Engineering & Dimensionality Reduction

| Module | Topic | Highlights |
|--------|-------|------------|
| 12 | Feature Scaling | StandardScaler, MinMaxScaler on Wine dataset (13 features) |
| 13 | Gradient Descent Projects | Boston housing, logistic regression with gradient descent |
| 19 | PCA | Eigendecomposition, 3D-to-2D, face images (LFW), breast cancer data |

### Deep Learning

| Module | Topic | Highlights |
|--------|-------|------------|
| 24 | Neural Networks (TensorFlow) | 3-layer NN on MNIST — **96% accuracy** |
| 24 | Neural Networks (sklearn) | MLPClassifier on various datasets |

### Projects

| Module | Project | Dataset | Approach |
|--------|---------|---------|----------|
| 17 | Text Classification | 20 Newsgroups (19,997 docs) | Multinomial Naive Bayes, NLP pipeline |
| 20 | Used Car Price Prediction | 297,222 records | Feature engineering, regression |
| 21 | CIFAR-10 Image Classification | 60,000 images | PCA + Random Forest / LR / SVM / KNN comparison |
| 22 | NLP | Movie reviews | Stemming, lemmatization, preprocessing |

---

## Datasets Used

| Dataset | Type | Size | Used In |
|---------|------|------|---------|
| Titanic | Classification | 891 records | Modules 05, 09, 11 |
| Boston Housing | Regression | 506 records | Modules 06, 13 |
| Iris | Classification | 150 samples | Modules 11, 15, 18 |
| Breast Cancer | Classification | 569 samples | Modules 16, 19 |
| Wine | Classification | 178 samples | Module 12 |
| CCPP | Regression | 9,568 records | Module 08 |
| Diabetes | Regression | 442 records | Module 06 |
| 20 Newsgroups | Text Classification | 19,997 docs | Module 17 |
| Used Cars | Regression | 297,222 records | Module 20 |
| CIFAR-10 | Image Classification | 60,000 images | Module 21 |
| MNIST | Image Classification | 70,000 images | Module 24 |
| LFW Faces | Dimensionality Reduction | 13,000+ images | Module 19 |

---

## Tech Stack

| Category | Libraries |
|----------|-----------|
| Data Processing | `pandas`, `numpy` |
| Machine Learning | `scikit-learn` |
| Deep Learning | `TensorFlow` |
| Visualization | `matplotlib` |
| NLP | `nltk` |
| Tree Visualization | `pydotplus`, `graphviz` |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/the-mrinal/ML-Notebook.git
cd ML-Notebook

# Install dependencies
pip install numpy pandas matplotlib scikit-learn tensorflow nltk pydotplus

# Launch Jupyter
jupyter notebook
```

Navigate to any numbered module folder and open the `.ipynb` files to begin.

---

## Repository Structure

```
ML-Notebook/
├── 00. data/                        # All datasets (CSV, images)
├── 02. NumpyArrays/                 # NumPy fundamentals
├── 03-04. Graphs & Plotting/        # Matplotlib
├── 05. Intro to Datasets/           # EDA on Titanic
├── 06. LinearRegression/            # 5 notebooks
├── 07. MultivariableRegression/     # 6 notebooks
├── 08. CombinedCycle/               # Regression project
├── 09. Logistic Regression/         # Binary classification
├── 10. ConfusionMetrics/            # Evaluation metrics
├── 11. DecisionTree Implementation/ # 5 notebooks
├── 12. featureScaling/              # Normalization techniques
├── 13. GradientDescentProjects/     # 5 notebooks
├── 15. NaiveBayes/                  # From-scratch + sklearn
├── 16. KNN Implementation/          # From-scratch + sklearn
├── 17. textClassificationProject/   # Full NLP pipeline
├── 18. SVM/                         # Support Vector Machines
├── 19. PCA/                         # Dimensionality reduction
├── 20. UsedCarProject/              # Real-world regression
├── 21. cifar10/                     # Image classification
├── 22. NLP/                         # Text preprocessing
├── 24. Neural Network/              # TensorFlow & sklearn NN
├── LICENSE
└── CODE_OF_CONDUCT.md
```

---

## License

MIT License - Copyright (c) 2018 Mrinal Chandra

---

## Topics

`machine-learning` `deep-learning` `python` `jupyter-notebook` `scikit-learn` `tensorflow` `data-science` `neural-networks` `classification` `regression` `nlp` `pca` `naive-bayes` `knn` `svm` `decision-tree` `gradient-descent` `mnist` `cifar10`
