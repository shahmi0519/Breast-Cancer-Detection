# 🔬 Breast Cancer Detection using the Wisconsin Dataset

This project uses the UCI Breast Cancer Wisconsin dataset to detect malignant and benign tumors using a deep neural network built with TensorFlow/Keras.

---

## 📁 Dataset

- **Source:** [UCI ML Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Instances:** 569
- **Features:** 30 numeric + diagnosis label (B = benign, M = malignant)

---

## 🧠 Model Overview

| Layer         | Units | Activation |
|---------------|--------|------------|
| Input         | 30     | -          |
| Hidden Layer 1| 16     | ReLU       |
| Hidden Layer 2| 8      | ReLU       |
| Output        | 1      | Sigmoid    |

---

## 📊 Evaluation Metrics

- Accuracy (Training vs Validation)
- Loss curves
- Confusion Matrix

---

## ⚙️ Installation

1. Clone the repo:
```bash
git clone https://github.com/yourusername/breast-cancer-detection.git
