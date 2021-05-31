# PCA_VS_AUTOENCODER
This project is to understand which will work better between pca and autoencoder, when we apply dimension reduction for prediction.
Problem is diabetes patient classification, dataset is taken from kaggle.

## What are Autoencoders?
Autoencoders are a special type of neural network architectures in which the output is same as the input. Autoencoders are trained in an unsupervised manner in order to learn the exteremely low level repersentations of the input data. These low level features are then deformed back to project the actual data. An autoencoder is a regression task where the network is asked to predict its input (in other words, model the identity function). These networks has a tight bottleneck of a few neurons in the middle, forcing them to create effective representations that compress the input into a low-dimensional code that can be used by the decoder to reproduce the original input.

## Take aways

* PCA worked better than autoencoder in this dataset
* we can improve our autoencoder by increasing number of layers
* Autoencoder needs more data to learn
