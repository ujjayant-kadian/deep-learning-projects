# Deep Learning Projects - TCD Deep Learning Course

## Overview

Welcome to the Deep Learning Projects repository for the TCD Deep Learning course, completed by Ujjayant Kadian. This repository contains seven projects covering a range of topics and applications in the field of deep learning. Each project focuses on different aspects of Python programming, linear regression, logistic regression, binary and multi-class classification, feedforward neural networks, convolutional neural networks, and a biomedical imaging project for tumor segmentation and classification.

## Projects

### Lab 0: Getting to know Python
- Introduction to Python programming.

### Lab 1: Linear Regression
- Implementation and understanding of linear regression.

### Lab 2: Logistic Regression
- Implementation and understanding of logistic regression.

### Lab 3:
#### Part 1 - Binary Classification
- Evaluate and compare ROC curves for different classifiers.
- Influence classifier performance by introducing class weights.

#### Part 2 - Multi-class Classification
- Evaluate and compare classifiers using the confusion matrix.
- Select classifiers with practical criteria.

#### Part 3 - Exercise
- Binary Classification project using a dataset with biological features to predict smoker/non-smoker status.

### Lab 4: Feedforward Neural Nets for Image Classification
- Implementation and training of feedforward neural networks for image classification.

### Lab 5: Convolutional Neural Nets for Image Classification
- Implementation and training of convolutional neural networks for image classification.

### Lab 6: Biomedical Imaging Project
#### Tumor Segmentation & Classification
- Dataset of ultrasound scans and segmentation maps for breast cancer tumor segmentation and classification.
- Train two separate neural networks for:
  - Classification Task: Predicting tumor status as benign, malignant, or normal.
    - Accuracy: 85%
    - Parameters: < 5 million
  - Segmentation Task: Predicting tumor segmentation map.
    - F1 Score: 72%
    - Parameters: < 3 million

#### Dataset Structure

##### Lab 6 Dataset
- Located in the 'dataset' directory.
- Structure:
  - benign/
    - input.npy
    - target.npy
  - malignant/
    - input.npy
    - target.npy
  - normal/
    - input.npy
    - target.npy

##### Image Properties
- Input ultrasound scans: 128x128x3 (RGB, pixel range: 0-1).
- Segmentation maps: 128x128x1 (1 for tumor presence, 0 for no tumor).

## Usage

Each project directory contains code, documentation, and necessary files to understand and reproduce the results. Refer to individual project folders for specific instructions on running and replicating experiments.

Feel free to reach out to Ujjayant Kadian for any questions or clarifications related to these projects.
