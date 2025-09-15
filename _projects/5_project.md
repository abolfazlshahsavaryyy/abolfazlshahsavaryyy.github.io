---
layout: page
title: MNIST — Neural Network from Scratch
description: A simple artificial neural network for MNIST implemented from scratch with gradient descent and mathematics
img: assets/img/mnist.png
importance: 3
category: work
github: https://github.com/abolfazlshahsavaryyy/mnist-ann-
---

This project is an **Artificial Neural Network (ANN) built from scratch** to classify the **MNIST handwritten digit dataset**.  
The focus is on understanding the **mathematics behind neural networks** — forward pass, loss functions, backpropagation, and weight updates — all implemented manually in Python.  

### 🔹 Key Features
- Implemented completely **from scratch** (no TensorFlow or PyTorch)  
- **Gradient Descent** optimization  
- Includes **mathematical formulas** for loss and gradient updates  
- Training with **batch and stochastic gradient descent**  
- Visualizations of **training loss** and **sample predictions**  

---

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/mnist.png" title="MNIST Neural Network" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Example output of the MNIST neural network implemented from scratch.
</div>

---

## ⚙️ Implementation Notes
- Example architecture: **784 → 128 → 64 → 10** with ReLU activations and softmax output  
- Weight initialization with small random values  
- Gradient descent with optional momentum  
- Evaluation: accuracy, confusion matrix, and predictions  

---

## 📂 Repository
You can view the full source code on GitHub:  
[MNIST ANN Repository](https://github.com/abolfazlshahsavaryyy/mnist-ann-)
