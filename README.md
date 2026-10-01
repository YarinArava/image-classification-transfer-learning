# Image Classification & Transfer Learning

Image classification experiments on CIFAR-10 and EuroSAT using
custom CNN architectures and pretrained deep learning models.

## Project Overview

The project explores two approaches to image classification:

1. Custom CNN architectures
2. Transfer Learning and Fine-Tuning

The same experimental pipeline was evaluated on two datasets:
- CIFAR-10
- EuroSAT

## Methods

- Exploratory Data Analysis
- Data Augmentation
- CNN architecture comparison
- Hyperparameter experiments
- Transfer Learning
- Fine-Tuning
- Confusion Matrix analysis

## Pretrained Models

- MobileNetV2
- ResNet50
- EfficientNetB0
- VGG16

## Datasets

### CIFAR-10
32×32 RGB images across 10 object classes.

### EuroSAT
64×64 satellite images across 10 land-use classes.

## Results

Transfer learning significantly improved classification performance
compared with the custom CNN baselines.

On EuroSAT, the strongest transfer-learning models achieved
approximately 96% test accuracy.

## Technologies

Python, Keras, PyTorch Backend, scikit-learn, NumPy, Matplotlib
