# ECG-AF-Classification

This repository contains code for Atrial Fibrillation (AF) classification using ECG signals. The project includes feature extraction code for preprocessing ECG data and a deep learning model built with TensorFlow/Keras for accurate AF detection.

## Feature Extraction

The feature extraction code (`Feature_Extraction`) processes ECG signals for effective AF classification. It reads ECG data from the PhysioNet database, filters signals for classes A, N, and O, and segments signals into fixed-length segments. Notably, it employs Continuous Wavelet Transform (CWT) to generate scalogram plots for visualizing signal characteristics.

## AF Classification Model

The AF classification model (`CTC`) is implemented using TensorFlow/Keras. The model utilizes a Convolutional Neural Network (CNN) with a Transformer-based architecture. The convolutional layers extract spatial features, while the Transformer blocks capture long-range dependencies. The model is trained on preprocessed ECG data to classify signals into AF categories.

