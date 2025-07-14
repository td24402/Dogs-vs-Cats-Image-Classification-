# Dogs-vs-Cats-Image-Classification

This project builds a Convolutional Neural Network (CNN) from scratch to classify images of cats and dogs. The model is trained on the Dogs vs Cats dataset and achieves perfect prediction on a test batch of 10 images.

# Project Overview

# Step	                                Description
Data Acquisition	                Used kagglehub to download dataset
Image Preprocessing	              Converted to grayscale, resized to 50x50 pixels
Data Shuffling & Splitting	      Shuffled and separated into features & labels
Model Architecture	              CNN with two convolutional layers
Model Training	                  Trained on ~70% data, validated on 30%
Model Evaluation	                Visualized predictions vs. true labels
TensorBoard Logging	              Enabled for performance visualization

# Tech Methods

    Python

    OpenCV (cv2)

    NumPy

    TensorFlow / Keras

    Matplotlib

    kagglehub for dataset download

    TensorBoard for training logs

# Image Preprocessing 

Converted all images to grayscale (color is not essential for classification)

Resized images to 50x50 pixels to reduce memory usage

Filtered out corrupt or unreadable images using try-except

Normalized pixel values to [0, 1] for model stability

# Training Logs with TensorBoard

# What I learned 

How to build a CNN from scratch using TensorFlow and Keras

Preprocessing large image datasets with OpenCV

Visualizing model predictions and using TensorBoard

Understanding model performance through grayscale simplification

Handling corrupted images in datasets

# Future Improvements

Add early stopping and learning rate decay

Use RGB images and test if color adds meaningful accuracy

Increase IMG_SIZE to capture more detail

Experiment with transfer learning (e.g., VGG16 or MobileNet)

Add test/train accuracy curves




