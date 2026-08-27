Multi-Class Digit Classifier

A PyTorch-based neural network designed to classify handwritten digits from the MNIST dataset. This project demonstrates a complete deep learning workflow, including dataset preparation, model development, training, evaluation, inference, visualization, and model saving.

Model Architecture

The classifier uses a fully connected neural network:

28 × 28 Image
     ↓
   Flatten
     ↓
784 → 128
     ↓
   ReLU
     ↓
128 → 64
     ↓
   ReLU
     ↓
64 → 10
     ↓
Digit Prediction
Technologies
Python
PyTorch
Torchvision
NumPy
Matplotlib

The model uses Cross-Entropy Loss with the Adam optimizer and automatically supports CUDA GPU acceleration when available. Training loss is recorded and visualized across epochs, while final performance is evaluated using the MNIST test dataset.

The project also demonstrates single-image inference, displaying the actual and predicted digit, and saves the trained parameters as a .pth file.

Key Concepts

Neural Networks • Forward Propagation • Backpropagation • Optimization • Classification • GPU Acceleration • Model Evaluation

Built as a practical project to strengthen PyTorch and deep learning fundamentals.
