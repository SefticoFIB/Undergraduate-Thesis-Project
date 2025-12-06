# 🩺 Pneumonia Detection Using Transfer Learning with CNN Ensemble  

A deep learning project focused on building an automated pneumonia detection system using chest X-ray images. Multiple pretrained CNN architectures were explored to determine the optimal model configuration for medical diagnostic support.

---

## 📌 Project Overview  

This project evaluates and compares multiple convolutional neural network (CNN) architectures using transfer learning, including **GoogLeNet, ResNet-18, and DenseNet-121**, for pneumonia classification.  
The final model is deployed as a **Flask-based web application**, enabling real-time prediction from uploaded X-ray scans.

---

## 🎯 Objectives

- Develop and evaluate multiple CNN architectures for pneumonia detection  
- Improve classification performance using augmentation and training optimization  
- Compare model performance using clinical metrics (Precision, Recall, F1, AUC)  
- Deploy the best-performing model into a functional web interface  

---

## 🧠 Model Architectures

| Model          | Status | Notes |
|----------------|--------|-------|
| **GoogLeNet**  | ⭐ Best Result | High performance with efficient inference time |
| ResNet-18      | Stable | Strong baseline with consistent generalization |
| DenseNet-121   | Good Depth | Strong feature extraction but required regularization to prevent overfitting |

---

## 📊 Dataset  

This project combines two well-known medical datasets:

- **RSNA Pneumonia Detection Dataset**
- **Kermany Chest X-Ray Dataset**

Preprocessing includes:

- Image resizing and normalization  
- Train/validation/test splitting  
- Class balancing  
- Data augmentation (rotation, flip, brightness, zoom)

---

## 📈 Performance Results

Best-performing model: **GoogLeNet**

| Metric | Score |
|--------|-------|
| Accuracy | **96.15%** |
| Precision | **96.45%** |
| Recall | **97.44%** |
| F1-Score | **96.94%** |
| AUC | **0.9904** |

<img width="486" height="442" alt="image" src="https://github.com/user-attachments/assets/0398ef58-15cb-4d55-ad87-4498fd0a791c" />

<img width="390" height="341" alt="image" src="https://github.com/user-attachments/assets/65a242b8-a707-4c0b-bd43-74f000f7c8f7" />



---

## 🚀 Deployment  

A lightweight **Flask application** was built to demonstrate real-world usage.

Features:

- Upload chest X-ray images  
- Automated preprocessing and inference  
- Prediction output: `Normal` or `Pneumonia`  

<img width="778" height="375" alt="image" src="https://github.com/user-attachments/assets/9902bf1f-4515-42e6-9482-551ec5f89ed6" />
<img width="779" height="376" alt="image" src="https://github.com/user-attachments/assets/b92fb48a-c975-4741-97d0-d4473b1bbcb0" />
<img width="774" height="376" alt="image" src="https://github.com/user-attachments/assets/30d0d6fc-540d-41d3-a867-12fc64c56562" />




---

## 🛠 Tech Stack  

| Category | Tools |
|----------|-------|
| Language | Python |
| Deep Learning | PyTorch / TensorFlow (depending on final model selected) |
| Deployment | Flask |
| Data | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| IDE | Google Colab / VS Code |

---
