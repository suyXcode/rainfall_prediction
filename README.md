# 🌧️ Rainfall Prediction Project

This project predicts whether it will rain using weather parameters and a **Machine Learning model** integrated into a **Django web application**.

---

## 🚀 Project Overview

The Rainfall Prediction Project is designed to help users forecast rainfall based on key weather inputs. It uses a machine learning model trained on historical data and provides a simple web interface built with Django for user interaction.

---

## 🧠 Features

- Predicts rainfall (Yes / No)
- Uses important weather parameters:
  - Precipitation
  - Maximum Temperature
  - Minimum Temperature
  - Wind Speed
- Machine Learning model using **Logistic Regression**
- Django-based web interface
- User-friendly input form and prediction output

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Backend Framework:** Django  
- **Machine Learning:** Scikit-learn (Logistic Regression)  
- **Data Processing:** Pandas, NumPy  
- **Frontend:** HTML, CSS, Django Templates  

---

## 📁 Project Structure
```bash
rainfall_prediction/
│
├── manage.py
├── README.md
├── requirements.txt
│
├── rainfall/ # Django project folder
├── predictor/ # Django app
│ ├── views.py
│ ├── models.py
│ ├── urls.py
│
├── model/
│ └── rfp.pkl # Trained ML model
│
├── templates/
│ └── index.html
│
├── static/
│ └── css/
│
└── dataset/ # Dataset (if included)

```

---

## ⚙️ How It Works

1. User enters weather data through the web interface.
2. Django backend loads the trained Logistic Regression model.
3. The model processes the input data.
4. Prediction result (Rain / No Rain) is displayed on the webpage.

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/suyXcode/rainfall_prediction.git
cd rainfall_prediction
```
### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
```

**Activate it:**

### Windows
```bash
venv\Scripts\activate
```

### Linux / macOS
```bash
source venv/bin/activate
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Server
```bash
python manage.py runserver
```
### 5️⃣ Open Browser
```bash
http://127.0.0.1:8000/
```

## 📈 Future Improvements

- Add advanced Machine Learning models (Random Forest, XGBoost)
- Integrate real-time weather API
- Improve UI with charts and animations
- Deploy on cloud platforms (Render, Railway, Heroku)

---

## 👨‍💻 Author

**Suyash Singh**  
B.Tech CSE | Machine Learning & Web Development Enthusiast  

🔗 GitHub: https://github.com/suyXcode
