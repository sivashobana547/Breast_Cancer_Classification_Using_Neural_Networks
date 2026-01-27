# Breast Cancer Classification Using Neural Networks

## 📌 Overview
This project uses a **Neural Network (NN)** to classify breast cancer tumors as **benign** or **malignant**. The model is trained on the **Breast Cancer Wisconsin dataset** from Scikit-learn and implemented using **TensorFlow/Keras**.

The goal is to demonstrate how deep learning can be applied to medical datasets for binary classification problems.

---

## 🧠 Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Samples: 569
- Features: 30 numeric features
- Target:
  - `0` → Benign
  - `1` → Malignant

---

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 🔄 Project Workflow
1. Load breast cancer dataset
2. Convert data to Pandas DataFrame
3. Perform exploratory data analysis
4. Split dataset into training and testing sets
5. Standardize feature values
6. Build neural network model
7. Train and validate the model
8. Visualize accuracy and loss

---

## 🏗️ Model Architecture
- Input Layer: 30 features
- Hidden Layer: Dense (20 neurons, ReLU activation)
- Output Layer: Dense (2 neurons, Sigmoid activation)
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy

---

## 📈 Results
- Achieves strong training and validation accuracy
- Accuracy and loss curves are visualized using Matplotlib
- Demonstrates effective classification of benign vs malignant tumors

---

## 🚀 How to Run
    ```bash
        pip install numpy pandas scikit-learn tensorflow matplotlib
        python breast_cancer_classification__using_nn.py


## 📊 Visualizations

Training vs Validation Accuracy

Training vs Validation Loss

## 📌 Use Cases

Medical data classification

Neural network learning project

Healthcare AI demonstrations

Academic mini-project
