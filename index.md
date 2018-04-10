# TrueBlue Talks: Machine Learning

First introductory talk about machine learning in TrueBlue.

Pre-requisites:
 - Python basic knowledge
 - Conda installed
 - Would be nice if everyone has the environment already installed, it takes time

Please watch the intro at [ML-Tour](https://sabau.github.io/ml-tour/)

## AI - ML - DL How they are related

<p align="center">
  <img alt="Relation of AI_ML_DL" src="./images/ai_ml_dl.png">
</p>

### Machine Learning vs Deep Learning on features

We will see the concept of features later on. 
For this moment consider it as the R/G/B channels values in an image, for each pixel in the early layers, edges or lines in the following, corners or line crossing in the middle layers, objects near the final layers and real world targets in the very final layer.

<p align="center">
  <img alt="Relation of AI_ML_DL" src="./images/machine-learning-vs-deep-learning.png">
</p>

## Machine Learning Problems

There are a variety of problems that can be tackled with ML, each have a different approach and resolution technique.

<p align="center">
  <img alt="Machine learning categories" src="./images/ml_problems.jpg">
</p>

## What we will see today

Two examples:
- Unsupervised
- Supervised: simple Neural network VS convNet

We will have to skip Recurrent NN, time series and general AI problems. Maybe in one of the next episodes.
Q-Learning, Capsule Network and Reinforcement Learning will be a nice topic, unfortunately I don't have time to prepare them in the foreseable future as they are far more complex to explain and setup.

### Unsupervised exmaple: kNN

It's one of the most easy to understand algorithm, and gives satisfaction! we will classify access to servers and see where anomalies lies.

<p align="center">
  <img alt="knn" src="./images/knn.gif">
</p>

### Supervised exmaple: images

#### What are we trying to solve

<p align="center">
  <img alt="classify-localize" src="./images/Classification_Localization.png">
  <img alt="mnist-fashion" src="./images/Detection_segmentation.png">
</p>

#### Our dataset

MNINT is a dataset with 10 integers to classify, too easy for our pourposes.
MNIST is the classical example here, but is has became too easy to solve and reach 99.7% accuracy.
I've found MINST-fashion where we will classify images of clothes, shoes etc. The performances here drops a bit so we will have more fun trying to solve it.

<p align="center">
  <img alt="mnist-fashion" src="./images/mnist_fashion-embeddings.gif">
</p>
