# Neural Network from Scratch – Fashion MNIST

This project implements a simple feedforward neural network **from scratch in Python**, using only foundational libraries like `numpy`, and trains it on a **the Fashion-MNIST dataset**.

### Features

- Manual implementation of forward/backward propagation
- ReLU activation & softmax + cross-entropy loss
- Batch training with gradient descent
- Evaluation with test accuracy (up to **98%**)
- No deep learning frameworks (e.g., TensorFlow, PyTorch)

### Architecture

- Input: 784 (flattened 28x28 images)
- Hidden Layers: [50 → 50] with ReLU activations
- Output: 3 neurons (for selected classes)
- Optimizer: SGD (manual update rule)
