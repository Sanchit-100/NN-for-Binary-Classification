# Simple Feedforward Neural Network for Binary Classification

This project implements a basic feedforward neural network for binary classification with the following architecture:

- **Input Layer**: 2 features  
- **Hidden Layer**: 1 neuron with sigmoid activation  
- **Output Layer**: 1 neuron (no activation function)

We use a synthetic dataset where:
- Label 0 samples: X comes from Normal distribution with mean [-1 -1] and covariance I
- Label 1 samples:  X comes from Normal distribution with mean [1 1] and covariance I
- 10 samples are drawn for each class (total 20 samples)  
- 50% of the data is used for training and 50% for testing.

---

## 🚀 Architecture & Training

- **Loss Function**: Mean Squared Error (MSE)
- **Training Algorithm**: Gradient Descent
- **Initialization**: All weights and biases are randomly initialized.
- **Epochs**: 1000
- **Learning Rate**: 0.1

---

## Test MSE
MSE = 0.0812

## Training plot vs epochs
![image](https://github.com/user-attachments/assets/3c3f8fa5-dee1-4d38-b286-0e506a67257b)
