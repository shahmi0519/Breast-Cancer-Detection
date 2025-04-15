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
  git clone https://github.com/shahmi0519/Breast-Cancer-Detection.git
  ```
2. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
3. Run the notebook:
  ```bash
  jupyter notebook notebooks/breast_cancer_detection.ipynb
  ```
---

## 💾 Model Export

The trained model is saved in:
  ```bash
  model/my_model.keras
  ```

You can load it later using:
  ```bash
  from tensorflow.keras.models import load_model
  model = load_model('model/my_model.keras')
  ```
---

## 📂 Project Structure

```bash
breast-cancer-detection/
├── notebooks/
│   └── breast_cancer_detection.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```
---

## ✍️ Author
**Ahamed Shahmi A.J**
- **📧 Mail**: [`shahmiahamed0519@gmail.com`](mailto:shahmiahamed0519@gmail.com)
- **🔗 LinkedIn**: [`Ahamed Shahmi`](https://www.linkedin.com/in/ahamed-shahmi-abduljabbar/)
- **💻 GitHub**: [`shahmi0519`](https://github.com/shahmi0519)

---
## 📝 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

