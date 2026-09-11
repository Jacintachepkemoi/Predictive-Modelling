 🤖 Predictive-Modelling

An end-to-end Python machine learning pipeline using a Random Forest Classifier to predict flower species with feature importance tracking.

---

 🌟 About My Journey & This Portfolio
 
After a brief hiatus from coding, I am officially back! This repository serves as a live, growing portfolio for my data science and machine learning projects, developed entirely inside the Google Colab ecosystem using Python 3.

🌸 Project 1: Iris Flower Species Classifier

This specific project utilizes the classic Iris dataset to predict flower species (Setosa, Versicolor, and Virginica) based on physical sepal and petal measurements.

  Tech Stack & Workflow
  
Environment: Google Colab (Jupyter Notebooks)
Libraries: Pandas, NumPy, Scikit-Learn
Algorithm: Random Forest Classifier (Ensemble method using 100 decision trees)
Workflow: Data Loading ➡️ DataFrame Structuring ➡️ Train/Test Split (80/20) ➡️ Model Training ➡️ Performance Evaluation

  Key Insights & Results
  
Model Accuracy:100.0% on the hidden test set. Due to the highly distinct and linearly separable nature of the standard Iris toy dataset, the Random Forest algorithm successfully mapped perfect classification boundaries.
Feature Importance Breakdown:
    🌲 Petal Length (44.0% impact) & Petal Width (42.2% impact): Combined, petal dimensions dictate over 86% of the model's predictive power.
    🌲 Sepal Length (10.8% impact): Acts purely as a minor tie-breaker.
    🌲 Sepal Width (3.0% impact): Found to be statistical noise with negligible impact on final classification.

