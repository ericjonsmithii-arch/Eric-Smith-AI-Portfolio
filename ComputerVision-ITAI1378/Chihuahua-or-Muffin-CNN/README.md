# Chihuahua or Muffin CNN

## Problem Statement

This project explored how a convolutional neural network can classify images that may appear visually similar. The model was trained to distinguish between Chihuahua dogs and muffins.

## Approach

The project used a convolutional neural network with multiple convolutional layers, ReLU activation, max pooling, dropout, and fully connected layers. Images were converted into tensors and processed so the model could learn visual patterns from each class.

## Results

The completed notebook demonstrated the full image-classification workflow, including image preprocessing, model construction, training, validation, and prediction.

The model learned patterns such as shapes, textures, edges, and color differences that helped separate Chihuahua images from muffin images.

## Key Findings

- Convolutional layers detect local visual patterns.
- ReLU activation helps the network learn nonlinear relationships.
- Max pooling reduces image size while preserving important features.
- Dropout helps reduce overfitting.
- Similar-looking image classes can still be separated through learned visual features.
- Model performance depends heavily on image quality and dataset variety.

## Technologies Used

- Python
- Google Colab
- PyTorch
- Torchvision
- Convolutional Neural Networks
- Matplotlib
- NumPy

## How to Run

1. Open the notebook in Google Colab.
2. Run each cell from top to bottom.
3. Allow the dataset and required libraries to load.
4. Review the model architecture, training output, and predictions.
