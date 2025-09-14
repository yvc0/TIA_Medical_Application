# 🏥 Medical Risk Prediction App

This is a simple **Streamlit-based web application** that predicts an individual's **health risk level** (Low, Medium, or High) based on basic medical and lifestyle details.  
It provides personalized **suggestions** for maintaining or improving health.

---

## 🚀 Features
- Easy-to-use **web interface** with input fields for:
  - Age
  - Blood Pressure
  - Blood Sugar
  - Cholesterol
  - BMI Category
  - Smoking Habit
  - Alcohol Consumption
  - Physical Activity
  - Family History of Disease
- Calculates a **Risk Score** using predefined rules.
- Displays prediction as:
  - ✅ Low Risk  
  - ⚠️ Medium Risk  
  - 🚨 High Risk  
- Provides **health suggestions** based on the prediction.

---

## 📂 Project Structure
```
medical-prediction-app/
├── medical_app.py   # Main Streamlit application
├── requirements.txt # Dependencies
└── README.md        # Project documentation
```

---

## 📦 Installation

1. **Clone this repository** (or copy project files):
   ```bash
   git clone https://github.com/your-username/medical-prediction-app.git
   cd medical-prediction-app
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Run the Application
Run the Streamlit app with:
```bash
streamlit run medical_app.py
```

The app will open in your browser at:
```
http://localhost:8501
```

---

## 📊 Example Usage
- Select **Age: 45**
- Blood Pressure: **High**
- Sugar: **Borderline**
- Cholesterol: **High**
- BMI: **Overweight**
- Smoking: **Occasional**
- Alcohol: **Occasional**
- Activity: **Low**
- Family History: **Yes**

👉 The app may predict **🚨 High Risk** and suggest consulting a doctor.

---

## 🛠 Requirements
Contents of `requirements.txt`:
```
streamlit
```

---

## 💡 Future Improvements
- Integrate with a **real medical dataset** and machine learning models.
- Add **charts & dashboards** for better visualization.
- Export results to **PDF or CSV**.
- Multi-user login with saved health reports.

---

## 📌 Disclaimer
⚠️ This app is for **educational purposes only** and does not replace professional medical advice.  
Please consult a doctor for accurate diagnosis and treatment.
