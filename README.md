# 🐧 Penguin Species Classification
Machine learning model predicting penguin species type based on penguin features from the Palmer Penguins Dataset.

## Project Overview
This project builds and evaluates classification models to determine a penguin’s species (Adelie, Chinstrap, or Gentoo) from various biological measurements such as flipper length, bill depth, and body mass.

The goal is to demonstrate fundamental data science and machine learning skills, including data cleaning, exploratory data analysis, model building, and evaluation.

## Dataset
- **Source:** [Palmer Penguins Dataset](https://raw.githubusercontent.com/liaochunyang/PIC16/refs/heads/main/PIC16A/data/palmer_penguins.csv)
- **Features:**  
  - Culmen length
  - Culmen depth  
  - Flipper length  
  - Body mass
  - Sex
  - Delta 15 N (o/oo)
  - Delta 13 N (o/oo)
  - Island  
- **Target:** Species (`Adelie`, `Chinstrap`, `Gentoo`)


## Tools and Libraries
- Python  
- pandas, numpy  
- matplotlib, sklearn 


## Results
- Machine Learning Models Tested: Support Vector Machine, K-Nearest Neighbors, Multinomial Logistic Regression 
- Best model: SVM on most recent run.
- Due to the random test splitting, each model gives us a different accuracy everytime, but all accuracy scores are consistently over 90%, and we were able to get an accuracy of 97%. Further, by using cross validation, we found the best hyperparameters for each model to train our data set. Our best model was our SVM model compared to our KNN and logistic regression models, which consistently got the highest accuracy. 
