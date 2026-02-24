# Advanced-Food-Recognition-and-Calorie-Tracking-System-Using-Machine-Learning
📌 Overview

This project implements an end-to-end machine learning pipeline for food image recognition and calorie estimation. The system uses convolutional neural networks (CNNs) trained with TensorFlow/Keras to classify food images and estimate nutritional values via real-time database queries. The trained model is exposed through a REST API for scalable inference.

📊 Dataset

Public food image datasets (e.g., Food-101 and custom curated samples)

Multi-class classification across diverse food categories

Images preprocessed using resizing, normalization, and augmentation techniques

🧠 Model Architecture

CNN-based architecture implemented in TensorFlow/Keras

Transfer learning with pre-trained backbones and custom classifier heads

Ensemble modeling to improve robustness and classification accuracy

⚙️ Training & Evaluation

Optimizer: Adam

Loss: Categorical Cross-Entropy

Batch training with data augmentation

Evaluation metrics: Accuracy and class-wise performance analysis

Result:

Achieved ~40% accuracy improvement over baseline single-model approach through ensemble learning and hyperparameter tuning

🚀 Inference & Deployment

Deployed trained model as a RESTful API using Flask/FastAPI

Supports real-time image uploads and predictions

Modular architecture allows easy integration with front-end or mobile applications

🔍 Key Learnings

Practical experience in model training, tuning, and evaluation

Designing ML systems for real-time inference

Handling end-to-end ML lifecycle from data ingestion to deployment

---

## ⚙️ Installation
Clone the repo:
```bash
git clone https://github.com/your-username/food-recognition-calorie-tracker.git
cd food-recognition-calorie-tracker
## Install dependencies:
pip install -r requirements.txt

## Run Streamlit app:
streamlit run app.py
