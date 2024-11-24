# Neural Network for MNIST Dataset

This project implements a simple neural network to classify handwritten digits from the MNIST dataset. 
The network is trained, validated, and tested using separate loops, providing performance metrics for each phase.
The point of this programme was to get a begining feel for neural nets and their math.

## Features
- **Dataset**: MNIST dataset (handwritten digits, 0-9).
- **Neural Network**:
  - Fully connected layers with ReLU activation.
  - Batch-based processing for training and validation.
- **Training**:
  - Backpropagation with weight updates.
  - Dropout for regularization.
- **Validation**:
  - Evaluates model performance on a separate validation set.
  - Reports error and accuracy metrics.
- **Testing**:
  - Final evaluation on an unseen test set to report generalization performance.
