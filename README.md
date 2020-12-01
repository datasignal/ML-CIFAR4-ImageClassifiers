# ML - CIFAR-4 Image Classification

The goal of this project is to build image classifiers using different models and techniques. We will use a subset of the CIFAR-10 data set with four categories: trucks, cars, airplanes, and ships. This project uses two different datasets :

1. A dataset containing 4'096 high-level features for each images extracted from thee OverFeat convolutional neural network that will be used to train : kNN, Decision Tree, Random Forest, SVM and Logistic Regression models
2. The images dataset to train fully connected and convolutional neural networks with Tensorflow 1.x

This project is an opportunity to train and compare different machine learning algorithms with a subset of the CIFAR-10 dataset to reduce computational requirements. Each step (aka model) is presented in its dedicated notebook.

The following packages are required to execute the notebook :
* `python`
* `numpy`
* `pandas`
* `scipy`
* `scikit-learn`
* `matplotlib`
* `seaborn`

If using `conda`, a ready to use environment can be created with the commands :
```bash
# Create the conda environment
> conda create -f environment.yml

# Activate the environment
> conda activate ml-cifar4

# Launch Jupyter notebook server
> jupyter notebook
```