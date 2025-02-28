# XOR Operation with TensorFlow and PyTorch

This document demonstrates the implementation of the XOR (exclusive OR) operation using both TensorFlow and PyTorch.

## TensorFlow Implementation

### Model Architecture

* A sequential model with:
    * One hidden layer with 2 units and ReLU activation.
    * One output layer with 1 unit and sigmoid activation.
* Compilation:
    * Optimizer: Adam
    * Loss Function: Binary cross-entropy
    * Metrics: Accuracy

### Training Data

* Input (X_data): [[0, 0], [0, 1], [1, 0], [1, 1]]
* Output (Y_data): [0, 1, 1, 0]

### Training

* Epochs: 50

### Evaluation

* The model's accuracy on the XOR dataset is evaluated.

### Results

* The model achieved an testing accuracy is 75% in both.
* The training accuracy of the model is 75% in both.

