# Handwritten-digit-recognition

# Project Overview
This project demonstrates a Handwritten Digit Recognition System built using the MNIST dataset. The system uses a deep learning model implemented with TensorFlow/Keras to classify digits (0-9) based on their pixel values. The project includes model training, evaluation, and prediction capabilities, as well as visualization of training metrics and results.

# Features

Data Preprocessing: Normalizes the MNIST dataset to improve training efficiency.

Model Architecture: A feedforward neural network with two hidden layers (128 units each) and a softmax output layer.

Training: Trains the model using the Adam optimizer and sparse categorical cross-entropy loss.

Evaluation: Achieves ~98% training accuracy and ~97% validation accuracy.

Prediction: Predicts handwritten digits from user-supplied images in .png format.

Visualization: Plots training/validation accuracy to help assess model performance.

# Technologies Used

Programming Language: Python
Libraries:

TensorFlow/Keras: Model building and training.

NumPy: Numerical computations.

OpenCV: Image preprocessing.

Matplotlib: Visualization of results.

os: File and directory management.

# Model Performance

Training Accuracy: ~99%

Validation Accuracy: ~97%

Test Loss: ~0.11

# Example Results

Test Accuracy: 97.49%

# Future Improvements

Implement a Convolutional Neural Network (CNN) for better accuracy.

Enhance preprocessing to handle non-MNIST styled images.

Build a user interface for easier image uploads and predictions.

# Acknowledgments

MNIST Dataset: Dataset for handwritten digit recognition.

TensorFlow Documentation: For guidance on building deep learning models.
