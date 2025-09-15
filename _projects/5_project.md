---
layout: page
title: MNIST — Neural Network from Scratch
description: A from-scratch artificial neural network for MNIST using gradient descent, with mathematical formulas and visualizations
img: assets/img/mnist.png
importance: 3
category: education
github: https://github.com/abolfazlshahsavaryyy/mnist-ann-
---

This project implements an **artificial neural network (ANN) from scratch** to classify the **MNIST** handwritten digit dataset.  
No deep-learning frameworks were used — the network, training loop, forward pass, and backpropagation were implemented manually to demonstrate the core mathematics and mechanics behind neural networks.

### Highlights
- ✅ **Network implemented from scratch** (layers, activations, weight initialization)  
- ✅ **Training with batch gradient descent / stochastic gradient descent**  
- ✅ **Mathematical derivations included** (loss, gradients, update rules)  
- ✅ **Visualizations** of training loss and sample predictions

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/mnist.png" title="MNIST Neural Network" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Example outputs and training visualizations from the MNIST neural network implemented from scratch.
</div>

---

## 🔬 Math & Training (concise)

**Loss (cross-entropy for one-hot label y and softmax output p):**

\[
\mathcal{L} = -\sum_{k} y_k \log p_k
\]

**Softmax output:**

\[
p_k = \frac{e^{z_k}}{\sum_j e^{z_j}}
\]

**Gradient of loss w.r.t. logits \(z\):**

\[
\frac{\partial \mathcal{L}}{\partial z_k} = p_k - y_k
\]

**Weight update (gradient descent):**

\[
W \leftarrow W - \eta \frac{\partial \mathcal{L}}{\partial W}
\]

Where \(\eta\) is the learning rate.  
Backpropagation applies the chain rule layer-by-layer to compute \(\frac{\partial \mathcal{L}}{\partial W}\) and \(\frac{\partial \mathcal{L}}{\partial b}\).

---

## ⚙️ Implementation notes
- Network architecture examples: **[784] → [128] → [64] → [10]** with ReLU activations and softmax output.  
- Weight initialization: small random values (e.g., Xavier/Glorot initialization recommended).  
- Optimizers: vanilla **(stochastic) gradient descent** implemented; experiments with momentum also included.  
- Regularization: simple L2 weight decay and dropout can be toggled for experiments.  
- Evaluation: accuracy, confusion matrix, and sample prediction visualizations saved during training.

---

## 📂 Repository
The full implementation, training scripts, dataset preprocessing, and visualizations are available on GitHub:

[MNIST ANN Repository](https://github.com/abolfazlshahsavaryyy/mnist-ann-)

---
