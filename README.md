# 🌿 Edge AI in Farming – Plant Disease Detection

## 📌 Overview

Plant diseases significantly impact agricultural productivity and global food security. Early detection of plant diseases can help farmers take timely action and reduce crop losses. Traditional disease detection methods rely heavily on manual inspection, which is time-consuming and requires expert knowledge.

This project implements an AI-based plant disease detection system using **deep learning and computer vision** to automatically identify plant diseases from leaf images. Such automated systems can assist farmers by providing faster and more accurate diagnoses.

The implementation is inspired by the research paper:
https://pmc.ncbi.nlm.nih.gov/articles/PMC12216444/

---

## 🚀 Features

* 🌱 Automated Plant Disease Detection
* 🧠 Deep Learning-based Image Classification
* 📷 Detects diseases from leaf images
* ⚡ Fast predictions using trained models
* 🌾 Supports smart agriculture applications
* 🧩 Can be integrated with Edge AI devices or mobile applications

---

## 🧠 Project Motivation

Plant diseases are one of the main causes of reduced agricultural yield. Many farmers depend on manual observation or expert consultation, which may be slow and inaccurate.

Recent advancements in **machine learning and deep learning enable automatic disease detection through computer vision**, making crop monitoring faster and more efficient.

This project aims to:

* Assist farmers in early disease identification
* Reduce crop losses
* Support precision agriculture systems

---

## 🏗 System Architecture

```
Leaf Image
     │
     ▼
Image Preprocessing
     │
     ▼
Data Augmentation
     │
     ▼
Deep Learning Model Training
     │
     ▼
Disease Classification
     │
     ▼
Prediction Output
```

---

## 🔬 Methodology

### 1. Data Collection

Plant leaf images dataset containing healthy and diseased leaves.

### 2. Preprocessing

* Image resizing
* Normalization
* Data augmentation

### 3. Model Training

* Convolutional Neural Networks (CNN)
* Transfer learning models (if applied)

### 4. Evaluation

* Accuracy
* Precision
* Recall
* Loss curves

Deep learning models can automatically learn patterns such as **leaf color variations, spots, and textures** to classify plant diseases.

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Google Colab
* Jupyter Notebook

---

## 📂 Project Structure

```
Edge-AI-in-Farming-Smart-Farming-Project
│
├── dataset/
│   ├── train/
│   ├── test/
│
├── models/
│   ├── trained_model.h5
│
├── notebooks/
│   ├── Train_plant_disease.ipynb
│
├── utils/
│   ├── preprocessing.py
│
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/yourusername/Edge-AI-in-Farming-Smart-Farming-Project.git
cd Edge-AI-in-Farming-Smart-Farming-Project
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the training notebook:

```
Train_plant_disease.ipynb
```

Steps:

1. Load the dataset
2. Train the model
3. Evaluate the model
4. Test predictions on leaf images

---

## 📊 Example Output

```
Input Image: Tomato Leaf
Predicted Disease: Early Blight
Confidence: 96.4%
```

---

## 🌍 Applications

* Smart Farming Systems
* Agricultural Monitoring Platforms
* Mobile Apps for Farmers
* Automated Crop Disease Detection
* Precision Agriculture

---

## 🔮 Future Improvements

* Deploy model on Edge AI devices
* Develop a mobile application for farmers
* Integrate IoT sensors for crop monitoring
* Implement real-time disease detection using camera feeds
* Expand dataset to support more crops and diseases

---

## 📚 Reference

Research Paper:

Automated Plant Disease Detection using Artificial Intelligence
https://pmc.ncbi.nlm.nih.gov/articles/PMC12216444/

---

