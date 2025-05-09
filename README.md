Predictive-Modeling-of-Kobe-Bryant-s-Shooting-Performance

Kobe Bryant Shot Prediction Analysis
This repository contains a predictive modeling analysis of Kobe Bryant's shooting performance throughout his 20-year NBA career.

Project Overview
Using machine learning techniques, I analyzed over 30,000 shots taken by Kobe Bryant to predict whether a shot would be successful based on various factors such as court location, game situation, and shot type. This project provides insights into shooting patterns and explores the factors that most influenced Kobe's shooting success.

Repository Contents
kobe_shot_analysis.ipynb: Jupyter notebook containing all code for exploratory data analysis and predictive modeling
write_up.md: Detailed analysis of findings (2000-3500 words)
data/: Directory containing the dataset
images/: Visualizations referenced in the write-up

Key Findings
Decision Trees performed best with 68.13% accuracy, narrowly outperforming Logistic Regression (68.11%)
Shot distance was the most influential predictor of shooting success
Kobe's exceptional midrange game challenges modern analytics' emphasis on threes and layups
Time pressure (seconds remaining) significantly affected shooting performance
Simple models outperformed more complex approaches, suggesting basketball shooting follows fairly straightforward patterns

Methods Used
Linear regression for relationship between shot distance and percentage
Logistic regression for binary classification
K-Nearest Neighbors
Decision Trees
Neural Network implementation with PyTorch

Data Source
The dataset comes from the "Kobe Bryant Shot Selection" competition on Kaggle and includes spatial, temporal, and contextual features for each shot attempt.
