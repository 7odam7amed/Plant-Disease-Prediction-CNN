# 🌿 Plant Disease Prediction using CNN

A Deep Learning project for classifying plant diseases using the PlantVillage dataset.  
The model is built using Convolutional Neural Networks (CNN) and deployed with Streamlit.

---

## 📌 Project Overview

This project detects plant diseases from leaf images.  
It supports multiple plant categories and disease types using a trained CNN model.

- 📊 Dataset: PlantVillage
- 🧠 Model: Convolutional Neural Network (CNN)
- 🖥️ Interface: Streamlit Web App
- 📦 Framework: TensorFlow / Keras

---

## 🗂️ Project Structure
Plant-Disease-Prediction-CNN/
│
├── app/
│   ├── trained_model/
│   │   └── plant_disease_prediction_model.h5
│   ├── class_indices.json
│   ├── config.toml
│   ├── credentials.toml
│   ├── dockerfile
│   ├── main.py
│   └── requirements.txt
│
├── model_training_notebook/
│   └── main.ipynb
│
├── test_images/
│   ├── test_apple_black_rot.JPG
│   ├── test_blueberry_healthy.jpg
│   └── test_potato_early_blight.jpg
│
├── .gitattributes
├── .gitignore
├── LICENSE
└── README.md


---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
git clone https://github.com/7odam7amed/Plant-Disease-Prediction-CNN.git
cd plant-disease-prediction-cnn

### 2️⃣ Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate   # On Windows

### 3️⃣ Install Dependencies
pip install -r "app/requirements.txt"

### 4️⃣ Run the Application
streamlit run app/main.py

The app will open automatically in your browser.

---

## 🖥️ Application Features

- Upload plant leaf images
- Real-time disease prediction
- Clean and simple Streamlit interface
- Displays predicted class with confidence score

---

## 🔍 Dataset

The model was trained on the PlantVillage dataset, which contains labeled images of healthy and diseased plant leaves across multiple categories.

---

## 🔮 Future Improvements

- Implement Transfer Learning (ResNet / EfficientNet)
- Add Top-3 Predictions
- Improve UI/UX design
- Deploy to Streamlit Cloud or HuggingFace Spaces
- Add confusion matrix visualization

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pillow
- Streamlit
