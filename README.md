# MLB Team Performance Prediction

This project uses machine learning models to predict Major League Baseball (MLB) team performance based on various statistical features. Two models are employed: a **Decision Tree** and a **Support Vector Machine (SVM)**, to predict the likelihood of a team finishing with a win percentage above .500.

## Features
- **Decision Tree** for regression-based prediction of win percentage.
- **SVM** for classification-based prediction of teams with a win percentage greater than 0.500.
- Evaluation metrics include precision, accuracy, recall, and the ROC curve with AUC (Area Under the Curve).

## Prerequisites
- R (version 4.0 or higher)
- R libraries:
  - `dplyr`
  - `rpart`
  - `rpart.plot`
  - `e1071`
  - `pROC`

Install the required R packages by running the following command in your R environment:

```r
install.packages(c('dplyr', 'rpart', 'rpart.plot', 'e1071', 'pROC'))