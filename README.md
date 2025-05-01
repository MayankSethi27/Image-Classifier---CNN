# Image Classifier using CNN

This project implements an **Image Classifier** that categorizes images into one of ten classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. The model is built using a **Convolutional Neural Network (CNN)** and trained on the CIFAR-10 dataset.

## Project Overview

The project demonstrates how to train a CNN model to classify images using a popular deep learning library, **TensorFlow/Keras**. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

The project involves:
- Loading and preprocessing the CIFAR-10 dataset
- Building a CNN model with multiple convolutional and pooling layers
- Training the model with the training dataset and evaluating it on the test dataset
- Visualizing the results and predicting the class of new images

## Model Architecture

The CNN model consists of the following layers:
1. **Convolutional Layers:** Used for feature extraction from images.
2. **Pooling Layers:** Used for downsampling and reducing the spatial dimensions.
3. **Fully Connected Layers:** Used for classification based on the features extracted by the convolutional layers.

## Data Description

The **CIFAR-10 dataset** consists of:
- **60,000** 32x32 color images.
- **10 classes** (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).
- **50,000 training images** and **10,000 test images**.
- Each class contains 6,000 images, evenly distributed between training and test datasets.

The images are labeled with a corresponding integer value (0 to 9) for each of the 10 classes.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/MayankSethi27/Image-Classifier---CNN.git
cd Image-Classifier---CNN
```
Install the required libraries:
```bash
pip install -r requirements.txt
```
Importing CIFAR-10 Dataset in Google Colab
```bash
import tensorflow as tf
(x_train, y_train), (x_test, y_test) = tf.keras.datasets.cifar10.load_data()
```
To run the Jupyter notebook and train the model:
```bash
jupyter notebook Image_Classification_CNN.ipynb

```
The notebook will guide you through the process of training and testing the CNN model, along with visualizations of the results.
## Conclusion

The CNN model successfully classifies images from the CIFAR-10 dataset into 10 categories. The project demonstrates key machine learning concepts like data preprocessing, model building, and evaluation.

