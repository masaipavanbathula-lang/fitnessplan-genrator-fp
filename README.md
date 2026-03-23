# 💪 FitPlan AI

FitPlan AI is an **AI-powered fitness planning web application** built using **Streamlit**.
It helps users generate **personalized workout plans** based on their **age, BMI, fitness goal, and available equipment**.

The application also provides **secure authentication using Password or OTP login**, along with a **weight tracking dashboard** for monitoring fitness progress.

---

## 🚀 Features

* 🔐 Login using **Password or OTP**
* 📧 Email **OTP verification during signup**
* 🤖 **AI Workout Plan Generator**
* 📊 **Weight Tracking System**
* 👤 **User Profile Management**
* 🎨 Modern **Glassmorphism UI Design**
* 💾 Data stored using **SQLite Database**
* 🔑 Secure session handling using **JWT Tokens**

---

## 🧠 AI Model Details

FitPlan AI uses a **Generative AI Model – Gemini 1.5 Flash** to generate structured workout plans.

### ⚙️ Model Function

The workout generation logic is implemented inside:

```python
generate_workout(name, age, goal, level, equipment, bmi)
```

### 🧩 Model Inputs

* User Name
* Age
* Fitness Goal
* Experience Level
* Equipment Availability
* BMI Value

### 📤 Model Output

* Day-wise workout split
* Warm-up exercises
* Strength training routines
* Cardio recommendations
* Rest and recovery guidance

---

## 🖥️ Application Pages

### 1️⃣ Login Page

Users can log in using:

* Email + Password
* Email + OTP verification

### 2️⃣ Signup Page

New users can create an account by entering:

* Full Name
* Age
* Gender
* Email Address
* Password
* Fitness Goal

After submitting details, an **OTP is sent to the user's email** for verification.

### 3️⃣ Dashboard

Once logged in, users can access:

* Dashboard overview
* Profile settings
* Workout plan generator
* Weight tracker
* Logout option

---

## 📈 Weight Tracker

Users can:

* Enter daily weight
* Save weight records
* View weight history chart

---

## 🛠️ Tech Stack

| Technology       | Usage                 |
| ---------------- | --------------------- |
| Python           | Backend               |
| Streamlit        | Web UI                |
| SQLite           | Database              |
| JWT              | Authentication        |
| Brevo / SendGrid | Email OTP             |
| Gemini API       | AI Workout Generation |

---

## 📂 Project Structure

```
FitPlan-AI/
│
├── app.py
├── database.py
├── auth.py
├── model.py
├── requirements.txt
├── README.md
└── screenshots/
```

---

## ⚙️ How to Run the Project

### Step 1 – Install Dependencies

```
pip install -r requirements.txt
```

### Step 2 – Run Streamlit App

```
streamlit run app.py
```

---

## 🔮 Future Enhancements

* Password hashing security (bcrypt)
* Diet plan AI generator
* Advanced workout history page
* BMI auto calculation
* Mobile responsive UI
* Deployment on Streamlit Cloud / AWS
* Integration with wearable fitness devices

---

