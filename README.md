# Fake Review Detection

# Overview

This project focuses on automated fake review detection using various machine learning and deep learning models. The implementation utilizes a diverse set of features generated from the Yelp dataset, addressing challenges such as imbalanced data, feature analysis, engineering, preprocessing, and hyperparameter tuning. The primary objective is to assess and compare the performance of models, including Random Forest, Support Vector Machine (SVM), and different variations of deep learning.

The Yelp dataset can be downloaded here: https://drive.google.com/drive/folders/1ZSiss9wGh1kvNgi4p83ZgcISYBSzOlwe?usp=share_link and save it in a new folder

Download FinalDataset.csv from: https://drive.google.com/file/d/1qI6Rp4QcIVcvfUpD1_fjwsgujXQ0KRT5/view?usp=share_link

# Findings

The project employs five types of models: Random Forest, SVM, Deep Learning, and two variations of deep learning with feature selection using Random Forest and SVM. Training and evaluation are performed with different feature sets, and the results show that Random Forest outperforms other models in terms of precision, recall, and F1 score. Feature importance analysis using SVM and Random Forest highlights date variance (DateVar) and activity time (ActivityTime) as crucial features. Scatter plots further distinguish genuine and fake reviews based on these top-selected features, providing insights into the models' decision-making processes.

Run the command to save all images and evaluation results in a new folder:

`python3 ./CODE/main.py`
