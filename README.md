# 🖐️ Hear-The-Sign

A machine vision project that predicts hand signs from images using Convolutional Neural Networks (CNNs) and transfer learning with **ResNet-18**.

---

## Project Overview

**Hear-The-Sign** is a deep learning-based image classification system that translates hand signs into textual labels. Initially built with a custom CNN, the model was later enhanced using **ResNet-18**, a pretrained convolutional neural network, due to performance limitations with the basic architecture.

---

## Objectives

- Recognize and classify hand sign images.
- Explore the impact of different deep learning architectures (Custom CNN vs ResNet-18).
- Improve accuracy and robustness using transfer learning.

---

## Model Architectures

### 1.**Custom CNN (Initial Approach)**
- Built using basic layers (Conv2D, MaxPooling, ReLU, etc.)
- Faced overfitting and lower accuracy due to limited depth and capacity.

### 2. **ResNet-18 (Final Approach)**
- Utilized **transfer learning** with pretrained ResNet-18 from PyTorch.
- Achieved significantly better performance and generalization.

---

## Dataset

- **Hand Sign Image Dataset**
- Includes labeled images of various hand signs.
- Split into training, validation, and test sets.

> Dataset Used : (https://huggingface.co/datasets/Marxulia/asl_sign_languages_alphabets_v03).

---

## 🛠️ Tech Stack

- **Language**: Python 🐍
- **Frameworks**: PyTorch, torchvision
- **Libraries**: NumPy, Matplotlib, Scikit-learn
- **Tools**: Jupyter Notebook / Colab

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Dhairya1910/Hear-The-Sign.git
   cd Hear-The-Sign
