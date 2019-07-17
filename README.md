# K-Nearest-Neighbor

Implementation of kNN classifier on CIFAR-10 dataset


Overview
============

The kNN classifier consists of two stages:
* During training, the classifier takes the training data and simply remembers it
* During testing, kNN classifies every test image by comparing to all training images and transfering the labels of the k most similar training examples
* The value of k is cross-validated


Dependencies
============

* Numpy 
* matplotlib
* scipy 
Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies


Usage
===========

To check the implementation of code, just open knn.ipynb and run the all the cells


Credits
===========

This is a part of Assignment #1 of [CS231n](http://cs231n.github.io/)
