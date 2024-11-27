# Vision Team Image Classification
#### Team : Hyeonjun Choi / Siyeon Lee / Jaeyeong Han

This repository contains code for an image classification project utilizing TensorFlow and Keras with pre-trained models. The project involves image preprocessing, augmentation, and training a custom classification model based on a pre-trained network.

## Features

- **Data Preparation**: Functions to load and label images from a directory structure.
- **Data Augmentation**: Utilizes `ImageDataGenerator` for augmentation during training and validation.
- **Custom Model Architecture**: Fine-tunes a pre-trained `InceptionResNetV2` model with additional dense layers for multi-class classification.
- **Training & Evaluation**: Supports metrics like accuracy for evaluating performance.

## Requirements

- Python 3.x
- TensorFlow >= 2.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV
- Seaborn
