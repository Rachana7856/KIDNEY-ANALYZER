# 🩺 Kidney Analyzer

A Machine Learning-based web application for predicting the likelihood of Chronic Kidney Disease (CKD) using patient health parameters. The application provides a simple web interface where users can enter medical information and receive prediction results in real time.

---

## 📌 Overview

Chronic Kidney Disease is a serious health condition that often goes undetected in its early stages. This project uses a pre-trained Machine Learning model to analyze patient data and assist in preliminary kidney disease risk assessment.

The application is built using Flask and integrates a trained model stored in a Pickle file for fast predictions.

---

## ✨ Features

- Predicts the likelihood of Chronic Kidney Disease
- User-friendly web interface
- Real-time prediction results
- Flask-based backend
- Pre-trained Machine Learning model
- Lightweight and easy to run locally

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Framework
- Flask

### Libraries
- Scikit-Learn
- Pandas
- NumPy

### Model Storage
- Pickle (.pkl)

### Version Control
- Git & GitHub

---

## 📂 Project Structure

```text
KIDNEY-ANALYZER
│
├── analyzer.py           # Main Flask application
├── kidney_model.pkl      # Trained ML model
├── requirements.txt      # Project dependencies
├── Procfile              # Deployment configuration
├── README.md             # Project documentation
└── kidney_app.log        # Application logs
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Rachana7856/KIDNEY-ANALYZER.git
```

### 2. Navigate to the Project Directory

```bash
cd KIDNEY-ANALYZER
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python analyzer.py
```

### 5. Open in Browser

```text
http://127.0.0.1:5000
```

---

## 🎯 Use Case

This project can assist healthcare professionals and students in understanding how Machine Learning can be applied to disease prediction systems. It demonstrates the integration of a trained ML model with a web application for real-time predictions.

---

## 🚀 Future Enhancements

- Improved user interface
- Model performance visualization
- Patient history tracking
- Cloud deployment
- Additional health prediction modules

---

## 👩‍💻 Maintainer

**Rachana Mehta**

GitHub: https://github.com/Rachana7856

---

## 🙏 Acknowledgement

This repository is a fork of the original project developed by **j123s**.

The project was successfully cloned, tested, documented, and maintained by **Rachana Mehta** for learning, experimentation, and understanding Machine Learning deployment using Flask.

Original Repository:
https://github.com/j123s/KIDNEY-ANALYZER
