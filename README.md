# Pattern-recognition-machine-learning


![Unknown-1](https://github.com/Ramahalharbi/Pattern-recognition-machine-learning/assets/139393175/f414d31a-1a9c-44d3-b9b8-807b766b8ce2)



Project Title

MAGIC Gamma Telescope

Overview

The MAGIC Gamma Telescope project was developed as part of a pattern regression project at University of Jeddah. The project focuses on simulating and analyzing high-energy gamma particles detected by a ground-based atmospheric Cherenkov gamma telescope using imaging techniques. Cherenkov gamma telescopes observe high-energy gamma rays by leveraging the radiation emitted by charged particles produced within electromagnetic showers initiated by the gammas in the atmosphere.

The goal of the MAGIC telescope is to detect and study gamma rays primarily originating from the accretion of black holes in active galactic nuclei and supernova remnants. The telescope captures the Cherenkov radiation, which is registered in the detector as pulses on photomultiplier tubes, forming a pattern called the "shower image." These patterns allow for statistical discrimination between primary gamma signals and images of hadronic showers caused by cosmic rays in the upper atmosphere.

The analysis involves performing a principal component analysis to extract Hillas parameters, characterizing the elongated clusters in the camera plane. Asymmetry along the major axis and other discriminating characteristics further aid in signal identification. The telescope's objective is to understand the sources of cosmic radiation and investigate phenomena like accretion and supernova remnants in the distant universe.

The project utilizes data generated through simulations, enabling researchers to study the telescope's performance, optimize data analysis algorithms, and develop pattern regression models to classify high-energy gamma rays accurately.

![Unknown-2](https://github.com/Ramahalharbi/Pattern-recognition-machine-learning/assets/139393175/1cff55a6-c163-4f04-8755-749f7c1312fd)



Model and Analysis

In this project, we explored various machine learning models to perform pattern regression and discriminate between high-energy gamma particles detected by the MAGIC Gamma Telescope. The following models were used in our analysis:

1- k-Nearest Neighbors (kNN): kNN is a simple and effective classification algorithm that assigns the class of a data point based on the class labels of its k-nearest neighbors in the feature space.

2- Naive Bayes: Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem. It assumes that the features are conditionally independent given the class label, which simplifies the computation and makes it efficient for high-dimensional datasets.

3- Logistic Regression: Logistic Regression is a linear classification algorithm that models the probability of a binary outcome. It is widely used for binary classification problems and can be extended to multi-class problems as well.

4- Support Vector Machine (SVM): SVM is a powerful algorithm for binary classification that finds the optimal hyperplane that best separates the data points belonging to different classes. It can be extended to handle multi-class problems through one-vs-one or one-vs-all approaches.

5- Random Forest: Random Forest is an ensemble learning method that combines multiple decision trees to improve performance and reduce overfitting. It is effective for both classification and regression tasks.

6- Neural Network (Neural Net): Neural Networks are a class of deep learning models inspired by the structure of the human brain. They are capable of learning complex patterns from data and are widely used for various machine learning tasks.

For each model, we performed data preprocessing  to prepare the input data. To evaluate the models' predictive capabilities and compare their performance, we utilized the Receiver Operating Characteristic (ROC) curve.

The ROC curve is a graphical representation of the trade-off between the true positive rate (TPR or sensitivity) and the false positive rate (FPR) as the classification threshold varies. The Area Under the Curve (AUC) is used as a single metric to measure the overall performance of each model. A higher AUC value indicates better discrimination ability.

Table of contents:
1- ipynb file 

2- project report as research paper


