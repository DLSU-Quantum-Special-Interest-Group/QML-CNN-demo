# Quantum Machine Learning Convolutional Neural Network (QML-CNN) Demo

[![Organization](https://img.shields.io/badge/Organization-DLSU%20Quantum%20SIG-005A36?style=for-the-badge&logo=academic-tree&logoColor=white)](https://github.com/DLSU-Quantum-Special-Interest-Group)
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PennyLane](https://img.shields.io/badge/PennyLane-QML-7F52FF?style=for-the-badge&logo=lightning&logoColor=white)](https://pennylane.ai/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Framework-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

[![GitHub Repo Stars](https://img.shields.io/github/stars/DLSU-Quantum-Special-Interest-Group/QML-CNN-demo?style=flat-square)](https://github.com/DLSU-Quantum-Special-Interest-Group/QML-CNN-demo/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/DLSU-Quantum-Special-Interest-Group/QML-CNN-demo?style=flat-square)](https://github.com/DLSU-Quantum-Special-Interest-Group/QML-CNN-demo/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/DLSU-Quantum-Special-Interest-Group/QML-CNN-demo?style=flat-square)](https://github.com/DLSU-Quantum-Special-Interest-Group/QML-CNN-demo/issues)

---

## 📌 About The Repository

This repository contains educational code, notebooks, and demonstrations on **Quantum Machine Learning (QML)** using hybrid **Quanvolutional Neural Networks (QCNNs)**. Developed by the **De La Salle University (DLSU) Quantum Special Interest Group**, this project showcases how variational quantum circuits (VQCs) can act as feature extractors within traditional Convolutional Neural Network architectures.

By replacing classical convolutional filters with random or variational quantum circuits, we transform input image patches into quantum states, execute entanglement and rotation operations, and measure expectation values to generate transformed feature maps for downstream classification.

Link: <https://colab.research.google.com/github/DLSU-Quantum-Special-Interest-Group/QML-CNN-demo/blob/main/qml_cnn_playground.ipynb>

---

## 🚀 Features

- ⚛️ **Quanvolutional Layer Implementation:** Custom quantum feature maps using parameterized quantum circuits (PQCs).
- 🖼️ **Image Classification Demos:** Hands-on examples applying hybrid models to standard datasets (MNIST, Fashion-MNIST, or custom binary/multiclass tasks).
- 📊 **Visualization Tools:** Plotting tools for feature maps, quantum circuit diagrams, and loss/accuracy curves.
- ⚡ **Simulator & Hardware Ready:** Configured to run on state-vector quantum simulators with support for hardware backends (e.g., IBM Quantum).

---

## 🛠️ Tech Stack & Dependencies

| Category | Technologies |
| :--- | :--- |
| **Language** | Python 3.8+ |
| **Quantum Frameworks** | PennyLane, Qiskit |
| **Deep Learning** | PyTorch / TensorFlow |
| **Data & Visualization** | NumPy, Matplotlib, scikit-learn |
