# 🥔 Potato Leaf Disease Classification using Deep Learning

This project implements a **Convolutional Neural Network (CNN)** to classify potato leaf images into different disease categories using **TensorFlow and Keras**. The goal is to enable **early detection of plant diseases**, helping farmers reduce crop loss and improve yield.

---

## 📌 Problem Statement
Potato crops are vulnerable to multiple leaf diseases that significantly affect productivity. Manual inspection is time-consuming and error-prone. This project automates disease detection using **computer vision and deep learning**.

---

## 🎯 Objectives
- Classify potato leaf images into disease categories
- Build an end-to-end CNN pipeline
- Achieve high accuracy using image preprocessing and augmentation
- Provide a scalable ML solution for agriculture technology

---

## 🧠 Model Overview
- Model Type: **Convolutional Neural Network (CNN)**
- Framework: **TensorFlow / Keras**
- Input Image Size: **256 × 256 × 3**
- Epochs: **50**
- Batch Size: **12**

---

## 🗂️ Dataset
- Image dataset organized using directory-based labels
- Loaded using `image_dataset_from_directory`
- Dataset split:
  - **Training:** 80%
  - **Testing:** 20%

> Dataset is expected in a compressed format (`Potato.rar`) and extracted during runtime.

---

## 🛠️ Tech Stack
- **Python**
- **TensorFlow**
- **Keras**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## ⚙️ Project Workflow
1. Dataset extraction and loading
2. Image preprocessing and batching
3. Dataset splitting (train/test)
4. CNN model architecture definition
5. Model training and validation
6. Performance visualization

---

## 📊 Visualization
- Sample images plotted using Matplotlib
- Class names extracted dynamically
- Training behavior observable via accuracy/loss trends

---

## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/your-username/potato-leaf-disease-classification.git

# Install dependencies
pip install tensorflow matplotlib numpy

# Open notebook
jupyter notebook Potato_leaf_Classification.ipynb
