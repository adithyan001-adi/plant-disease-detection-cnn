# 🌿 Plant Disease Detection using Deep Learning

This project aims to build a **deep learning–based image classification system** to identify plant diseases from leaf images.

✅ Project Status: Working Model Implemented

---

## 📌 Objective

The goal of this project is to:
- Classify plant leaf images into **healthy or diseased categories**
- Support **multiple plant disease classes**
- Use **Convolutional Neural Networks (CNNs)** for image-based classification

---

## 🧠 Planned Approach

- Image preprocessing and normalization
- Data augmentation for better generalization
- CNN-based architecture using TensorFlow/Keras
- Model evaluation using accuracy, precision, recall, and F1-score
- Visualization using confusion matrix

---

## 📂 Dataset (Planned)

**New Plant Diseases Dataset (Augmented)** – Kaggle  
(The dataset will not be included in this repository due to size constraints.)

---

## ⚙️ Technologies (Planned)

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab (GPU)

---

## 🚀 Roadmap

- [ ] Dataset setup and exploration
- [ ] CNN model implementation
- [ ] Model training and optimization
- [ ] Performance evaluation
- [ ] Documentation and results

---

## 📌 Notes

This repository is under active development.  
Details, results, and implementation will be updated progressively.


## 🧠 Trained Model

A trained CNN model is included in this repository:


- File size: ~16 MB  
- Framework: TensorFlow / Keras  
- Input shape: 128 × 128 × 3  
- Output classes: 38 plant disease categories
## ▶️ Load Pre-trained Model

```python
import tensorflow as tf

model = tf.keras.models.load_model(
    "models/plant_disease_cnn.keras"
)

