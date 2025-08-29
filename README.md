# Advanced-Food-Recognition-and-Calorie-Tracking-System-Using-Machine-Learning
Developed an end-to-end ML system for food recognition and calorie tracking using CNNs, MLPs, and RNNs. Achieved 73% classification accuracy and reduced calorie estimation error to 164 kcal MAE. Deployed via Flask APIs and Streamlit for real-time user interaction.
## 📖 Description
Traditional calorie tracking is error-prone and time-consuming. This system automates the process using:
- **CNN (MobileNetV2)** for food classification (73.08% test accuracy on Food-101).
- **MLP regression model** for calorie estimation (Mean Absolute Error of 164 kcal).
- **RNN (LSTM)** for dietary trend prediction (120 kcal MAE on synthetic intake data).
- **Flask APIs & Streamlit UI** for real-time user interaction, deployed on Heroku with <2s latency.

---

## 🚀 Features
- Food image recognition from datasets like Food-101 & UEC-Food256.
- Calorie estimation integrated with USDA nutritional data.
- Dietary trend analysis using recurrent networks.
- Scalable deployment with Flask APIs and Streamlit front-end.
- Modular design for easy upgrades and integration.

---

## 🛠 Tech Stack
- **Languages:** Python  
- **Libraries:** TensorFlow, Keras, scikit-learn, OpenCV, NumPy, Pandas, Streamlit  
- **Tools:** Google Colab (GPU), Flask, Docker-ready deployment  
- **Datasets:** Food-101, UEC-Food256, USDA API  

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
