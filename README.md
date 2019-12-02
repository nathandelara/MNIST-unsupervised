# MNIST-unsupervised
Unsupervised classification of MNIST digits.

We show how to get a **0.92 V-score** using
* [scikit-learn](https://scikit-learn.org/stable/)
* [scikit-network](https://scikit-network.readthedocs.io/en/latest/)

A small grid search yields a score of **0.94** for the following parameters:
* Embedding dimension = **44**.
* Number of neighbors, k = **6**.
* Resolution = **0.5**.
