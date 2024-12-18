# Disease Prediction Classifier using Machine Learning

This project is a disease prediction system based on the symptoms provided by the user. The goal of this project is to predict the disease by combining multiple machine learning models such as **Random Forest**, **SVM**, and **Naive Bayes**. The project also provides functionality to train the models, validate them, and use them for predicting diseases given a set of symptoms.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Model Training](#model-training)
- [Disease Prediction Function](#disease-prediction-function)
- [Saving and Loading Models](#saving-and-loading-models)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project implements a robust classifier for predicting diseases based on a given set of symptoms. It uses a combination of three machine learning models:
- **Support Vector Machine (SVM)**
- **Naive Bayes**
- **Random Forest Classifier**

These models are trained on a dataset that includes various symptoms and their corresponding diseases. After training, predictions are made by combining the outputs of these classifiers and taking a majority vote.

### Features:
- Train models on a dataset containing symptoms and diseases.
- Combine predictions from multiple models (SVM, Naive Bayes, Random Forest).
- Provide disease predictions by inputting symptoms.
- Visualize model performance using confusion matrix and accuracy metrics.

## Technologies Used

- **Python**
- **Scikit-learn**: Machine learning library for training models.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib/Seaborn**: For visualizations like confusion matrix.
- **joblib**: For saving and loading models.
- **Google Colab**: For training models and running the code in a cloud environment.

## Getting Started

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/jsnodal/disease-prediction-classifier.git
cd disease-prediction-classifier
