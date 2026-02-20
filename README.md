# Lung Cancer Detection using Deep Learning

## 📌 Project Overview
This project presents a deep learning–based approach for lung cancer detection using CT scan images. A transfer learning model based on **VGG16** is used to classify lung CT scans into three categories:
- **Normal**
- **Benign**
- **Malignant**

The goal of this project is to assist in early detection of lung cancer by leveraging convolutional neural networks and medical image analysis.

---

## 🧠 Model Architecture
- Base Model: **VGG16 (Pre-trained on ImageNet)**
- Transfer Learning with fine-tuning
- Custom dense layers for multi-class classification

---

## 🗂 Dataset & Preprocessing
- Input images: Lung CT scan images (grayscale)
- Grayscale images converted to **3-channel RGB** for VGG16 compatibility
- Image resizing and normalization
- Data augmentation applied to improve generalization
- 🔗 **Dataset Link:**  
[Click here to access the dataset](https://www.kaggle.com/datasets/hamdallak/the-iqothnccd-lung-cancer-dataset)

---

## ⚙️ Technologies Used
- **Python**
- **TensorFlow**
- **Keras**
- **OpenCV**
- **NumPy**
- **Matplotlib / Seaborn**

---

## 📊 Model Performance
- **Test Accuracy:** 94.55%
- Evaluation Metrics:
  - Confusion Matrix
  - ROC–AUC Curves
  - Classification Report (Precision, Recall, F1-score)

---

## 💾 Model Saving
- Trained model saved in **`.h5` format**
- Ready for deployment or further fine-tuning

---

