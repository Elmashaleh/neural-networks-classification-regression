# Neural Networks for Classification & Regression

A hands-on deep learning project exploring **neural network training, hyperparameter experimentation, and model evaluation** across two different machine learning tasks: image classification and numerical regression.

The project compares multiple neural network configurations to understand how architectural changes affect model performance and generalization.

## Project Highlights

| Task | Dataset | Best Reported Result |
|---|---|---|
| Image Classification | Fashion-MNIST | ~89.2% Test Accuracy |
| Regression | California Housing | R² ≈ 0.7702 |

## 1. Fashion-MNIST — Image Classification

**Objective:** Train a neural network to classify grayscale clothing images into 10 categories.

### Approach
- Prepared the Fashion-MNIST dataset for neural network training.
- Trained and evaluated different neural network configurations.
- Experimented with architectural changes, including additional neurons and dropout.
- Compared model performance and examined generalization behavior.
- Used classification metrics and a confusion matrix to evaluate predictions.

**Best reported test accuracy: approximately 89.2%.**

## 2. California Housing — Regression

**Objective:** Use a neural network to estimate housing values from numerical input features.

### Approach
- Prepared the California Housing dataset for regression.
- Trained and compared multiple neural network configurations.
- Evaluated prediction errors using MAE, MSE, and RMSE.
- Used R² to measure how well the model explained variation in the target variable.

### Best Reported Results

| Metric | Value |
|---|---:|
| MAE | 0.3842 |
| MSE | 0.3011 |
| RMSE | 0.5488 |
| R² | 0.7702 |

These metrics reflect the best reported regression experiment in the project.

## Technologies & Concepts

- Python
- TensorFlow / Keras
- Jupyter Notebook
- Neural Networks
- Classification and Regression
- Hyperparameter Experimentation
- Dropout and Generalization
- Model Evaluation

## Repository Contents

This repository is intended to contain the original project notebooks and supporting academic report.

The project covers two complementary applications of neural networks: classification using image data and regression using structured numerical data.

## Learning Outcomes

Through this project, I gained practical experience in:

- Building and evaluating neural networks for different prediction tasks.
- Comparing baseline and modified model configurations.
- Interpreting classification accuracy and regression error metrics.
- Understanding the impact of neural network design choices.
- Documenting experimental results and model limitations.

## Project Context

This work was completed as an academic machine learning project. The reported results come from the experiments documented in the project report.

The models are educational experiments and are not presented as production-deployed systems.

## Author

**Motaz Mashaleh**  
B.Sc. Computer Engineering — Hashemite University, Jordan

GitHub: https://github.com/Elmashaleh
