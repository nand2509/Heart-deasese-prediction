 

# ❤️ Heart Disease Prediction System

A **Machine Learning-based web application** that predicts the likelihood of heart disease based on patient health parameters. This project uses a **Random Forest Classifier** trained on medical data to provide accurate and fast predictions.

---

## 📌 Overview

Heart disease is one of the leading causes of death worldwide. Early detection can significantly improve treatment outcomes.

This project aims to:

* Analyze patient health data
* Predict the probability of heart disease
* Provide quick and reliable results via a web interface

---

## 🧠 How It Works

1. **User Input**

   * User enters health parameters through a web form

2. **Data Processing**

   * Input data is preprocessed and formatted

3. **Model Prediction**

   * Pre-trained **Random Forest model** is loaded
   * Prediction is made based on input features

4. **Result Display**

   * System shows whether the person is at risk of heart disease

---

## 📂 Project Structure

```id="k3ks42"
Heart-disease-prediction/
│
├── templates/                         # HTML templates (UI)
├── .devcontainer/                     # Dev container setup
├── heart.csv                          # Dataset used for training
├── random_forest_classifier_model.pkl # Trained ML model
├── app.py                             # Web app (Flask)
├── main.py                            # Model training script
├── README.md                          # Documentation
```

---

## ⚙️ Installation

```bash id="n7f2s1"
git clone https://github.com/your-username/Heart-disease-prediction.git
cd Heart-disease-prediction

pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash id="1q9z8x"
python app.py
```

Then open in browser:

```
http://127.0.0.1:5000/
```

---

## 📊 Dataset Features

The model uses medical attributes such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol Level
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Slope of Peak Exercise ST Segment
* Number of Major Vessels
* Thalassemia

---

## 🤖 Model Details

* Algorithm: **Random Forest Classifier**
* Trained on: `heart.csv` dataset
* Output:

  * `0` → No Heart Disease
  * `1` → Heart Disease Detected

---

## 💡 Features

* ✅ Simple and user-friendly UI
* ✅ Fast predictions
* ✅ Pre-trained ML model
* ✅ Easy to deploy
* ✅ Lightweight and efficient

---

## ⚡ Future Improvements

* Add more advanced ML models (XGBoost, Neural Networks)
* Improve UI/UX design
* Add real-time patient monitoring
* Deploy on cloud (AWS/GCP/Azure)
* Add model explainability (SHAP, LIME)

---

## 🧠 Tech Stack

* Python
* Flask
* Scikit-learn
* Pandas / NumPy
* HTML / CSS

---

## ⚠️ Disclaimer

This project is for **educational purposes only** and should not be used as a substitute for professional medical advice.

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📜 License

MIT License

---
 

 
