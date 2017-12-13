## Celestial-classification

## Overview

Classification of the celestial objects (stars, galaxis and quasars) is an important issue in astrophysics. It provides a better undrestanding of the universe and its content. In particuar, using bright quasars as reference points, we can create the most detailed three-dimensional map of the universe. 
I utilise the DR12 (the final data release of the SDSS-III) release of the Sloan Digital Sky Survey (SDSS) for this purpose. I use both spectroscopic and photometric data from DR12 database.

For a review of the phsyics of the problem and details of the database I used, refere to follwoing website or similar ones

https://www.quora.com/What-is-the-difference-between-a-quasar-and-a-star http://skyserver.sdss.org/dr7/en/help/docs/QS_UserGuide.asp
http://www.sdss.org/dr12/algorithms/magnitudes/
http://www.astroml.org/examples/datasets/plot_sdss_filters.html

This work is more like a comparison among different algorithms used for the classification of celestial objects in a pedagogical manner for the purpose of education thoses physics and data science students and resaerchers. We start with some data munging and features slection . We then apply the following algorothms:
### 1.Logistic Regression
  #### 1.1.cross validation logistic regression
  #### 1.2.Decision boundary for logistic regression
### 2.Support Vector Machine (SVM)
### 3.KMeans
### 4.KNN 
### 5.Ensemble Classifications
  #### 5.1.Random Forest Algorithm
  #### 5.2.XGB Classifier (Extreme Gradient Boosting (XGBOOST))
### 6.Decision Trees Classifier
### 7.Evaluation of the Random Forest classifier by bootstrap sampling

For each model, we also evaluate the classfiers. The result can be found in the algorithm_comparison file.









