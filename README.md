# Neural Networks from Scratch — Forward & Backprop by Hand

This repository showcases two simple neural network implementations built entirely from scratch in Python, without using machine learning libraries. It demonstrates a clear understanding of core ML concepts including forward propagation, backpropagation, loss calculation, and gradient descent optimization.

These mini-projects are designed for educational purposes and illustrate how neural networks learn — one with linear transformations, the other with a non-linear hidden layer.

---

## 📂 Projects Overview

### 1. 🔁 Two-Layer Linear Network (No Activation)

A basic network with:
- **One input layer**
- **One intermediate linear layer**
- **One output layer**

####  Highlights
- No activation functions — fully linear
- Manual forward and backward pass
- Mean Squared Error (MSE) loss
- Gradient descent updates


####  Use Case
Perfect for visualizing how gradients flow and how weights evolve with no non-linearities.

---

### 2.  Feedforward Network with a Sigmoid Hidden Layer

A more complete example introducing non-linearity:
- **2 input features**
- **1 hidden neuron (sigmoid activation)**
- **1 output neuron (sigmoid activation)**
- **Manual backpropagation via chain rule**

#### Learning Workflow
- Sigmoid activation + its derivative
- MSE loss
- Chain-rule based backward pass
- Gradient descent weight updates


