# 🧠 Neural Network Classifier – A, B, C Recognition (NumPy Only)

This project implements a **simple neural network from scratch using NumPy** to classify binary pixel images of the letters **A, B, and C**. It is submitted as part of **Assignment 7: Module 11**.

---

## 📌 Objective

- Implement a **2-layer neural network** using matrix operations.
- Train it to classify 5x6 binary patterns of the letters A, B, and C.
- Use only **NumPy** (no TensorFlow, no PyTorch).
- Visualize predictions using `matplotlib`.

---

## 🧠 What You Will Learn

- Weight initialization
- Feedforward computation
- Sigmoid activation and its derivative
- Backpropagation
- Mean squared error (MSE) loss
- Epoch-based training
- Visualization of results

---

## 🧾 Data

No external dataset is required. The input consists of:
- Hand-crafted 5x6 binary patterns of:
  - A
  - B
  - C

---

## 🛠️ Technologies Used

- Python
- NumPy
- matplotlib

---

## 📈 Results

- Trained with 10,000 epochs
- Loss decreases over time
- Achieved **perfect classification** on known patterns A, B, and C

---

## 🖼️ Sample Output
Expected: A, Predicted: A, Probabilities: [[0.98, 0.01, 0.01]]
Expected: B, Predicted: B, Probabilities: [[0.01, 0.97, 0.02]]
Expected: C, Predicted: C, Probabilities: [[0.01, 0.02, 0.98]]
