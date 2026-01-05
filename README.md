# 🩺 Pregnancy Wellness Assistant (MaternalMind AI)

An **AI-powered Pregnancy Wellness Assistant** designed to support expecting mothers by tracking emotional well-being, pregnancy milestones, and daily health activities through a secure, privacy-focused web application.

---

## 📌 Project Overview

The **Pregnancy Wellness Assistant** is a web-based application built with **Python and Streamlit** that uses **Artificial Intelligence (AI)** to analyze emotions from **voice and text inputs**, track pregnancy-related data, and provide trimester-specific wellness insights.

The system prioritizes **privacy**, with all user data stored **locally** and no dependency on cloud services for core features.

---

## 🎯 Key Features

### 🧠 Emotion Analysis

* **Voice Emotion Recognition**

  * Upload audio files (WAV, MP3, M4A)
  * Extract MFCC and acoustic features
  * Classifies emotions into pregnancy-relevant categories
* **Text Emotion Analysis**

  * NLP-based mood detection from text input
  * Contextual emotional insights

### 🤰 Pregnancy Tracking

* Week-by-week pregnancy milestones
* Baby kick counter
* Symptom severity tracking
* Daily wellness check-ins (mood, energy, sleep, appetite)

### 🥗 Health & Lifestyle Logging

* Nutrition and meal logging
* Exercise activity tracking
* Vitamin and supplement reminders
* Trimester-based recommendations

### 📊 Reports & Data Export

* PDF wellness summaries
* Visual charts for emotional trends
* Export data in CSV/JSON formats
* Printable reports for healthcare consultations

### 🔐 Privacy & Security

* Local data storage (SQLite)
* No external API calls
* Secure authentication
* Password hashing (SHA-256)

---

## 🛠️ Technologies Used

### 🔧 Development & Tools

* **Language:** Python 3.9+
* **Framework:** Streamlit
* **Version Control:** Git & GitHub
* **IDE:** VS Code / PyCharm

### 🤖 AI & Machine Learning

* TensorFlow / PyTorch
* Librosa (audio processing)
* NLP models for text emotion analysis

### 📦 Backend & Storage

* SQLite (local database)
* Pandas & NumPy
* FPDF (PDF report generation)

### 📈 Visualization

* Plotly
* Streamlit UI components

---

## 🧱 System Architecture

* **Frontend:** Streamlit web interface
* **Backend:** Python business logic
* **Database:** SQLite (local)
* **ML Layer:** Pre-trained emotion analysis models

Architecture follows a **monolithic design** with modular components for scalability and maintainability.

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/hamzaajmal8484-max/Pragnancy-Wellness-Assistant.git
cd Pragnancy-Wellness-Assistant
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
streamlit run app.py
```

---

## ⚠️ Disclaimer

> This application is **not a medical device** and does **not provide medical diagnosis or treatment**.
> It is intended for **emotional support and wellness tracking only**.
> Users should always consult qualified healthcare professionals for medical advice.

---

## 📚 Documentation

* **Software Requirements Specification (SRS)** included
* Diagrams:

  * Use Case Diagram
  * ER Diagram
  * Class Diagram
  * Activity Diagram
  * Deployment Diagram

---

## 👨‍🎓 Academic Information

* **Student:** Hamza Ajmal
* **Degree:** BS Software Engineering
* **Institution:** The Islamia University of Bahawalpur
* **Supervisor:** Ms. Tayyaba Rashid
* **Session:** Spring 2022 – 2026

---

## 📬 Contact

For questions or collaboration:

* **GitHub:** [hamzaajmal8484-max](https://github.com/hamzaajmal8484-max)

---

## ⭐ Acknowledgements

* IEEE SRS Standards
* Streamlit Community
* Open-source AI & ML libraries

---

### ✅ Next Step (IMPORTANT)

After adding `README.md`, run:

```bash
git add README.md
git commit -m "Add professional README"
git push
```
