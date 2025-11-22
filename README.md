Diabetes Prediction Model

This project contains a complete machinelearning pipeline for predicting the likelihood of diabetes based on patient health metrics. It includes data preprocessing, model training, evaluation, and reproducible code in a Jupyter Notebook.

Overview

The goal of this model is to classify whether a patient is at risk of diabetes using structured clinical data. The workflow follows standard machinelearning practices and is built for clarity, reproducibility, and ease of experimentation.

Key Features

Dataset Loading & Inspection: Reads the diabetes dataset and explores structure and distribution.

Data Cleaning: Handles missing or zero-value entries with appropriate imputation.

Feature Scaling: Applies StandardScaler to normalize numerical features.

Train/Test Split: Creates a reliable 80/20 split for unbiased evaluation.


Neural Network Model:

Uses TensorFlow/Keras

Dense fully-connected architecture

Binary classification with sigmoid activation

Model Evaluation: Reports accuracy and loss on the test set.


Tech Stack

Python 3.x

Pandas / NumPy

Scikit-Learn

TensorFlow / Keras

Jupyter Notebook


How to Run

Install required libraries:

pip install pandas numpy scikit-learn tensorflow notebook


Launch the notebook:

jupyter notebook


Open diabetes ai model.ipynb and run the cells in order.

Project Structure
.
├── diabetes ai model.ipynb   # Full training + evaluation workflow
├── diabetes.csv              # Dataset used for model training
└── README.md                 # Project documentation

Results

The baseline model achieves approximately 71% training accuracy and 73% test accuracy, with potential for improvement through:

Hyperparameter tuning

Architecture adjustments

Additional data preprocessing

Feature engineering

License

This project is available for educational and research use.