# Books-Rating-Prediction-Using-Semi-Supervised-Learning

This repository presents an approach for predicting book ratings using semi-supervised learning techniques. The project involves training a supervised base model, specifically a Random Forest Classifier, and then utilizing various semi-supervised algorithms, including SelfTrainingClassifier, LabelPropagation, and LabelSpreading, to make book rating predictions.

## Notebook Description

In this project, we delve into the task of book rating prediction through the lens of semi-supervised learning. The process consists of two main phases:

**Random Forest Base Model Training:** We start by training a supervised base model using labeled book rating data. The base model is implemented using a Random Forest Classifier, which serves as a foundation for subsequent semi-supervised learning steps.

**Semi-Supervised Prediction:** Leveraging the trained Random Forest base model, we employ multiple semi-supervised algorithms to predict book ratings for unlabeled data. The algorithms we explore include:

 **SelfTrainingClassifier:** An iterative approach that labels unlabeled instances based on the base model's predictions.
 **LabelPropagation:** A graph-based algorithm that propagates labels among similar data points.
 **LabelSpreading:** A variant of LabelPropagation with smoothing effects.

## Contents

- [Notebook](TFIDF_H2O.ipynb): Jupyter Notebook containing the analysis.
- [Data](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews): Sample dataset used for the analysis.
- [README.md](README.md): This file, providing an overview of the repository.


## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/BahauddinKalyani/Books-Rating-Prediction-Using-Semi-Supervised-Learning.git
