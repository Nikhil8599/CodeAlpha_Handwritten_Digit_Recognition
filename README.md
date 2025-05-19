# CodeAlpha_Handwritten_Digit_Recognition

# 🔢 Handwritten Digit Recognition using ANN (0–9)

This project is a **Handwritten Digit Recognition System** built using a **Feedforward Artificial Neural Network (ANN)**. It was developed as part of my **#CodeAlpha Internship** to recognize handwritten digits from 0 to 9 using the **MNIST dataset**.

---

## 🚀 Features

- ✅ Predicts handwritten digits from 0 to 9
- ✅ Trained on the standard MNIST dataset (60,000 training & 10,000 test images)
- ✅ Uses a simple yet efficient ANN architecture
- ✅ Visualizes model performance (accuracy & loss plots)
- ✅ Predicts digits from custom images
- ✅ Lightweight and beginner-friendly

---

## 🧠 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Google Colab**

---

## 🗂 Dataset

- **MNIST Dataset**  
  Loaded directly via `tensorflow.keras.datasets.mnist`
  - 28x28 grayscale images
  - 10 classes (digits 0–9)

---

## 🧱 Model Architecture

- **Input Layer:** 784 neurons (28x28 image flattened)
- **Hidden Layer(s):** 
  - Dense (128 units) + ReLU
- **Output Layer:** 
  - Dense (10 units) + Softmax
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam
- **Epochs:** 10 (modifiable)
- **Batch Size:** 128
