# Fingerprint Blood Group Classification using Deep Learning

# Overview
This project implements a deep learning-based image classification model to classify blood groups from fingerprint images. 
It uses a Convolutional Neural Network (CNN) trained on a dataset of fingerprint images categorized by blood group.

# Dataset
- The dataset is stored in dataset_blood_group/, with subdirectories for each blood group.
- Images are preprocessed using ImageDataGenerator (rescaling and validation split).

# Model Architecture

The model is a Deep CNN with:

- 4 Convolutional Layers (ReLU activation, MaxPooling)
- Flatten & Dense Layers
- Dropout (0.5) to prevent overfitting
- Softmax Output Layer for multi-class classification
- Future Improvements
- Creating a frontend for this.
- Increase dataset size for better generalization.
- Fine-tune hyperparameters (learning rate, dropout, batch size).
