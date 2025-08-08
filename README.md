# Machine-Learning-Assignment
# 🧠 Digit Recognition using Artificial Neural Network (ANN)

This project uses an Artificial Neural Network (ANN) to recognize handwritten digits from the **MNIST dataset**. It is built and trained using **TensorFlow/Keras** in **Google Colab**.

---

## 📌 Problem Statement

Recognize handwritten digits (0–9) using a machine learning model.  
Since image data is complex, we use an ANN that can learn patterns from pixel values to predict the correct digit.

---

## 🚀 Why ANN?

We used **ANN** because:
- It is simple and effective for image classification.
- It works well on structured datasets like MNIST.
- It can handle non-linear data through multiple layers and activation functions.

---

## 📊 Dataset Used

- **MNIST Dataset** (Built-in in Keras)
- Contains:
  - 60,000 training images
  - 10,000 test images
  - Each image is a 28×28 grayscale image (values 0 to 255)

---

## 🧠 Model Architecture

| Layer          | Type        | Units | Activation |
|----------------|-------------|-------|------------|
| 1              | Flatten     | -     | -          |
| 2              | Dense       | 256   | ReLU       |
| 3              | Dense       | 128   | ReLU       |
| 4              | Dense       | 64    | ReLU       |
| 5              | Dense       | 10    | Softmax    |

---

## ⚙️ Training Details

- **Loss Function:** `sparse_categorical_crossentropy`
- **Optimizer:** `Adam`
- **Epochs:** 10
- **Batch Size:** 32
- **Validation Split:** 10%

---

## 🧪 Results

- Accuracy: ~98% on test data
- Loss decreases consistently with epochs
- Model generalizes well to unseen digits

---

## 📁 Files

- `Digit_Recognition.ipynb` – Colab notebook with the entire code
- `README.md` – Project description
