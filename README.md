# 🧠 Breast Cancer Classification with Neural Network

## 📌 Overview
This project implements a **Neural Network (NN)** using **TensorFlow/Keras** to classify breast cancer tumors as **malignant** or **benign** based on the **Breast Cancer Wisconsin Dataset** from `sklearn.datasets`.

The pipeline includes:
- Data loading & preprocessing
- Neural Network model creation
- Training & validation
- Performance visualization
- Predictive system for new data

---

## 📊 Dataset
- **Source**: Built-in dataset from `sklearn.datasets.load_breast_cancer()`
- **Features**: 30 numerical features describing cell nuclei characteristics
- **Target**:
  - `0` → Malignant (cancerous)
  - `1` → Benign (non-cancerous)

---

## ⚙️ Features of the Project
- Data loading from `sklearn.datasets`
- Data preprocessing & standardization (`StandardScaler`)
- Building a **Sequential Neural Network** with:
  - Input layer (Flatten)
  - Hidden layer (Dense with ReLU activation)
  - Output layer (Dense with Sigmoid activation for binary classification)
- Model compilation using **Adam** optimizer & **Sparse Categorical Crossentropy**
- Model training with validation split
- Accuracy & loss visualization
- Evaluation on test data
- Predictive system for real-time classification

---

## 🛠️ Tech Stack
- **Language**: Python 3
- **Libraries**:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow` / `keras`

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/breast-cancer-classification-nn.git
cd breast-cancer-classification-nn
