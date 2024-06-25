# CIFAR-10 Multi-class Classification using Transfer Learning with VGG16

## Project Overview

This project demonstrates how to perform multi-class classification on the CIFAR-10 dataset using transfer learning with the VGG16 model in Keras.


## Dependencies

- Python 3.x
- TensorFlow 2.x
- Keras
- Matplotlib


## Project Details

### Data Preprocessing

- Normalizes and preprocesses images using VGG16 preprocessing utilities.
- Converts labels to one-hot encoding for multi-class classification.

### Model Architecture

- Uses the pre-trained VGG16 model as a feature extractor.
- Adds additional layers for classification (dense layers with dropout for regularization).

### Training and Evaluation

- Compiles the model with Adam optimizer and categorical cross-entropy loss.
- Implements callbacks for learning rate scheduling and model checkpointing.
- Trains the model on preprocessed CIFAR-10 data for 10 epochs.

### Results Visualization

- Visualizes training and validation accuracy and loss over epochs.
- Displays model predictions on validation data with actual and predicted labels.

### Outcome

- Achieves high accuracy on both training (98.28%) and validation (88.67%) datasets.
- Demonstrates effective transfer learning in image classification tasks.


