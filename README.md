# Mental-Health-Bhutan-Streamlit

# Mental Health Stress Level Predictor (Bhutan)

A Streamlit web app that predicts stress levels based on lifestyle, mood, and personal habits.  
This project uses a Random Forest model trained on synthetic data generated at runtime.

---

## 🚀 Live Demo
Deploy easily using Streamlit Cloud:
https://share.streamlit.io

---

## 📌 Features
- Predicts stress level: **low**, **medium**, or **high**
- Interactive sliders for:
  - Age  
  - Sleep hours  
  - Social interaction  
  - Work/Study stress  
  - Physical activity  
  - Mood score  
- Machine learning model generated dynamically  
- No external dataset required  

---

## 🧠 Model
The app synthesizes 600 rows of random, realistic mental-health-related data.  
A `RandomForestClassifier` is trained each time the app loads (cached for performance).

---

## 📦 Installation

### **1. Clone the repository**
