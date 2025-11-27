# 🌾 CaneGuard AI — Sugarcane Leaf Disease Detection

CaneGuard AI is a deep-learning-based web application that helps detect and classify sugarcane leaf diseases from images. The system uses a trained convolutional neural network to assist farmers, agronomists, and researchers in early disease detection and better crop management.

---

## 🚀 Project Overview

Sugarcane is one of the most important agricultural crops in many countries. However, leaf diseases such as mosaic, red rot, rust, and yellowing can significantly reduce crop yield and quality.

Traditional disease detection relies on manual inspection by experts, which can be slow, expensive, and not always accessible.

**CaneGuard AI** solves this problem by providing an AI-powered tool that can analyze a simple leaf image and return:

- The predicted disease class
- Confidence level of the prediction
- Class probability distribution
- Basic disease descriptions and suggested actions
- A downloadable PDF report

---

## 🎯 Project Objectives

- Automatically classify sugarcane leaf images into disease categories
- Support early detection to reduce crop damage
- Provide farmers and engineers with fast and accessible decision support
- Present predictions in an interpretable and user-friendly interface

---

## 🧠 Model & Approach

- Model Architecture: **EfficientNet (Transfer Learning)**
- Framework: **TensorFlow / Keras**
- Input Image Size: **224 × 224**
- Number of Classes: **5**
  - Healthy
  - Mosaic
  - RedRot
  - Rust
  - Yellow

The model was fine-tuned on a labeled dataset of sugarcane leaf images. Images were resized, standardized, and processed to ensure consistent input to the neural network.

---

## 🗂️ Dataset

We used a publicly available labeled dataset of sugarcane leaf images obtained from Kaggle.

The dataset contains images across five categories:
- Healthy
- Mosaic
- RedRot
- Rust
- Yellow

*(Note: Dataset is not included in this repository due to size constraints.)*

---

## 🖥️ Web Application Features

The Streamlit web app provides:

✅ Image upload  
✅ Camera capture via browser  
✅ Real-time disease prediction  
✅ Confidence score visualization  
✅ Class probability table and bar chart  
✅ Disease explanation and suggested actions  
✅ Downloadable PDF report (with timestamp and image)

---

## ⚙️ How to Run the Project Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/caneguard-ai.git
cd caneguard-ai
