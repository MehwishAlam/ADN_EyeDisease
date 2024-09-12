# ADN Eye Dataset Classification 🧠👁️

This repository contains a Convolutional Neural Network (CNN) model built to classify eye images from the ADN Eye Dataset into three categories:

  AMD (Age-related Macular Degeneration)
  
  DME (Diabetic Macular Edema)
  
  NORMAL

The model is implemented using Keras and TensorFlow to aid in the automatic diagnosis of eye diseases based on medical imaging.

Project Overview

The goal of this project is to provide an AI-based solution for classifying medical eye images into three specific categories: AMD, DME, and NORMAL. This project can assist ophthalmologists in diagnosing these conditions with higher speed and accuracy.

### Dataset

The ADN Eye Dataset is composed of grayscale images categorized into:

  AMD: Images representing Age-related Macular Degeneration.
  
  DME: Images depicting Diabetic Macular Edema.
  
  NORMAL: Healthy, unaffected eye images.

### Preprocessing

Images are resized to 128x128 pixels.

Normalized pixel values (0-255 scaled to 0-1).

### Model Architecture

This CNN architecture consists of:

  Input Layer: Grayscale images of size 128x128.
  
  Convolutional Layers: Feature extraction from images using filters.
  
  MaxPooling Layers: Downsampling to reduce spatial dimensions.
  
  Dense Layers: Fully connected layers for classification.
  
  Dropout Layers: Added for regularization.
  
  Output Layer: Softmax layer to classify into one of the three categories.

The model is compiled with the Adam optimizer and uses categorical cross-entropy loss.

### Results

  Training Accuracy: > 93%
  Validation Accuracy: > 97%
  
