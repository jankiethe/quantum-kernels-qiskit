# quantum-kernels-qiskit
Explore how quantum circuits can be used as kernel functions for machine learning, using Qiskit. This project demonstrates quantum-enhanced feature maps and SVM classification with quantum kernel estimation on real or simulated quantum hardware.

# Quantum Kernels with Qiskit 🧠⚛️

This repo explores the use of **quantum circuits as kernel functions** for machine learning, using **Qiskit**. The goal is to understand how quantum feature maps can be used to compute kernel matrices for classification tasks (e.g., SVMs).

## 🧩 What’s Inside

- Implementation of quantum feature maps (`ZZFeatureMap`, etc.)
- Quantum kernel matrix evaluation
- Classical SVM using quantum kernel
- Experiments on synthetic datasets
- Simulators and ready-to-run IBMQ backend support

## 🚀 Getting Started

```bash
pip install qiskit qiskit-machine-learning scikit-learn matplotlib
