# A collection of small machine learning/deep learning projects 

* imdb sentiment prediction
* iris
* mnist
* tech stock analysis
* more are coming

Some of the notebooks were also upload to Kaggle:
[link](https://www.kaggle.com/asterfung/code)


--------------------------------------------------------------------------------------------------------
below are brief informations of each small project

## imdb_sentiment_prediction
* this project was later moved to an repository of its own
* [link here](https://github.com/aster-fung/hk_job_scraping)

## iris
The iris was published in 1936 for biological taxonmic problem. It includes 150 data entries (50 samples for each species). This dataset is a famous "hello world" dataset for machine learning classification. One of the iris species is linearly seperable from the other two while the remaining two iris species cannot be linearly seperated from each other. This project aims to practice data visualization and benchmark various machine learning classifiers. 
* exploratory data analysis: correlation analysis 
* classification models: Logreg, knn, SVM, decision tree, random forest, adaboost, xgboost
* most classifiers have >90% test accuracies

## mnist
The mnist dataset of handwritten digits, which has 60000 examples and 10000 test examples was invented by Y. LeCun, C. Cortes and C. Burges. It is the foundational dataset for deep learning learners to practice computer vision. The project aimed to identify handwritten digits with the generic artifical neural network (ANN) and convolutional neural network(CNN)
* a convolutional neural network inspired by LeNet-5 was builded
* val accuracy > 0.98

## tech_stock_analysis
Stock information was tech industry stocks were fetched via yfinance api and analysed.
* correlation analysis
* daily value at risk with bootstrap method and Monte Carlo simulation
