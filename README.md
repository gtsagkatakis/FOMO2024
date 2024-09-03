# FOMO2024_code

using data from https://github.com/lucainnocenti/ML-classification-of-VVBs/tree/master

# ML Classification of VVBs

This repository contains code and resources for visualizing and classifying images of Vector Vortex Beams (VVBs) using Convolutional Neural Networks (CNNs). The dataset and problem are inspired by the work provided in [ML-classification-of-VVBs](https://github.com/lucainnocenti/ML-classification-of-VVBs/tree/master).

## Project Overview

The aim of this project is to develop and train a deep learning model that can accurately classify images of Vector Vortex Beams into their respective categories. The dataset includes images organized into 15 distinct classes, each representing a unique type of VVB.

### Dataset

The dataset used in this project is derived from the [ML-classification-of-VVBs repository](https://github.com/lucainnocenti/ML-classification-of-VVBs/tree/master). The dataset is split into training and test sets, with 20 training images per class.

- **Training Data:** Located at `/content/dataset/15classes_split_20trainperclass/train`
- **Test Data:** Located at `/content/dataset/15classes_split_20trainperclass/test`

Each class in the dataset corresponds to a different type of VVB, and the images are labeled according to their respective classes.

### Project Structure

- **`train_cnn_VVBs.ipynb`**: A Jupyter Notebook that contains the code for training a Convolutional Neural Network (CNN) model to classify the VVB images. The notebook also includes code for evaluating the model's performance on a test set.


