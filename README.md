# 🔥 Forest Fire Prediction System (ML + Flask)

## 📌 Project Overview

This project is a **Machine Learning web application** built using **Flask** that predicts the likelihood of forest fires based on environmental conditions.

It uses a trained **Ridge Regression model** and takes user input through a web interface to generate predictions in real-time.

---
## 🌐 Live Demo

🔗 Deployed Project Link:  
http://forest-fire-env.eba-8amrfqwa.ap-south-1.elasticbeanstalk.com

☁️ Successfully deployed on AWS Elastic Beanstalk using Flask and Gunicorn.

## ☁️ Deployment

The project is deployed on AWS Elastic Beanstalk.

Deployment Steps:
1. Created Flask application
2. Added Procfile for Gunicorn
3. Configured AWS CLI and EB CLI
4. Deployed application on AWS Elastic Beanstalk
5. Hosted live ML prediction web app on cloud

## 🧠 Technologies Used

- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- HTML/CSS
- AWS Elastic Beanstalk
- Gunicorn
- Git & GitHub

## 🚀 Features

* 🌡️ Input environmental parameters (Temperature, Humidity, Rain, etc.)
* 🤖 Machine Learning prediction using Ridge Regression
* 🌐 Web interface using Flask
* ⚡ Real-time prediction output
* 📊 Data preprocessing using StandardScaler

---

## 📂 Project Structure

```
Project1/
│── application.py
│── models/
│     ├── ridge.pkl
│     ├── scaler.pkl
│── templates/
│     ├── index.html
│     ├── home.html
│── notebooks/
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone <your-repo-link>
cd Project1
```

---

### 2. Create Virtual Environment

```
python -m venv venv
```

Activate it:

**Windows (PowerShell):**

```
.\venv\Scripts\Activate.ps1
```

---

### 3. Install Dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```
python application.py
```

Open in browser:

```
http://127.0.0.1:5000/
```

---

## 📥 Input Features

The model takes the following inputs:

* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rain
* FFMC (Fine Fuel Moisture Code)
* DMC (Duff Moisture Code)
* ISI (Initial Spread Index)
* Classes
* Region

---

## 📤 Output

* Predicts forest fire intensity/value based on input features.

---

## ⚠️ Notes

* Ensure `ridge.pkl` and `scaler.pkl` are present inside the `models/` folder.
* The model was trained using **Scikit-learn**.
* Version mismatch may show warnings but does not affect execution.

---

## 📌 Future Improvements

* Add better UI (Bootstrap / React)
* Deploy on cloud (Render / AWS)
* Add visualization dashboard
* Improve model accuracy

---

## 👩‍💻 Author

Akanksha Ghule

🔗 GitHub:
https://github.com/Akankshaghule/testforestfires

🌐 Live Project:
http://forest-fire-env.eba-8amrfqwa.ap-south-1.elasticbeanstalk.com
for prediction output:http://forest-fire-env.eba-8amrfqwa.ap-south-1.elasticbeanstalk.com/predictdata
## ⭐ If you like this project, give it a star!
