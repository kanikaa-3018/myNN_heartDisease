# Heart Disease Prediction Neural Network

This project implements a **custom neural network from scratch** to predict the likelihood of heart disease. The network uses a **sigmoid activation function** and a **linear hypothesis model**, trained and tested on the Heart Disease Dataset. This project demonstrates a hands-on understanding of neural network structure, forward propagation, and training dynamics.

---

## Model Overview

* **Architecture:** Single-layer neural network built without high-level frameworks
* **Activation Function:** Sigmoid, ideal for binary classification
* **Hypothesis:** Linear hypothesis, calculated as

  $$
  \text{Output} = \text{Activation(Weights * Input + Biases)}
  $$
* **Input:** Features from the Heart Disease Dataset
* **Output:** Binary prediction (presence or absence of heart disease)

---

## Training Summary

* **Epochs:** 1000
* **Learning Rate:** 0.01
* **Evaluation Metric:** Accuracy
* **Best Result:** **65% test accuracy**

---

## Key Features

* Custom neural network implementation provides deeper understanding of training mechanics
* Insightful exploration of binary classification using basic neural network principles
* Framework-agnostic approach emphasizes foundational ML skills

---

## Future Improvements

* Extend to multi-layer architectures for higher predictive performance
* Tune hyperparameters (learning rate, epochs, batch size) for optimization
* Apply feature engineering and normalization to improve generalization

---

## Example Workflow

1. Load the Heart Disease Dataset
2. Initialize the network with weights and biases
3. Train the network using forward and backward propagation
4. Evaluate predictions on the test set and measure accuracy

