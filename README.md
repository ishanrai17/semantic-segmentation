# Semantic Segmentation Project

This repository provides a simple setup to experiment with semantic segmentation models. It includes:
- Data loading utilities
- Model definitions
- Training and evaluation scripts

## Model Description
A Convolutional Neural Network based on U-Net architecture used to handle multi-class (pet, boundary, background) segmentation. Encoders learn feature representations, while decoders reconstruct segmentation masks for each class.

## Getting Started
1. Clone the repository.
2. Run the training script (in colab).

## Results
This image belongs to the testing set of the Oxford-IIIT Pet dataset under TensorFlow datasets.

![Input](results/sample.png)

The classifier outputs a one-hot encoding of 3 classes for each pixel, which we transform into this image.

![Ground Truth](results/sample_result.png)

