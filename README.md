# Mental Health AI App

This is a **FastAPI + React + MySQL** application that helps monitor **stress levels**, provide **coping strategies**, and allow **event logging & journaling**.

## Overview
### Mental Health AI System

- Emotion Detection & Analysis: Uses a webcam to detect emotions and analyze text input for signs of stress or emotional distress.
- Event Logging & Stress Prediction: Users log upcoming events (e.g., exams, meetings), and AI predicts stress levels based on event type.
<!-- - Journaling & Self-Reflection: Users can write journal entries related to logged events, tracking mood changes over time. -->
- Secure Data Storage: Stores emotions, events, and journal entries in a MySQL database for tracking stress trends.
- AI-Based Text Analysis: Analyzes user input to detect signs of frustration, anxiety, or emotional distress.
- Privacy & Security: No unnecessary data collection, and user information is protected.

<!-- Future improvements could include real-time behavioral monitoring and additional accessibility features. -->

## Features
- **Emotion Detection** from face scans 
- **Text Sentiment Analysis** using NLP 
- **Event Logging** & Predictive Stress Analysis 

---

## **Local Setup Guide**
Follow these steps to **run the app locally**.

### **Prerequisites**
**Python 3.10+**  
**Node.js 18+**  
**MySQL Server**  
**Git Installed**  

## **1. Install Required Packages**
in terminal run:
```bash
pip install -r requirements.txt
```

---

## **1.1 Clone the Repository**
```bash
git clone https://github.com/yourusername/mental-health-ai.git
cd mental-health-ai
```

## **2. Install Backend**
### Navigate to backend folder
```bash
cd backend
```
# Install Dependencies
```python
pip install -r requirements.txt
```
### Run FastAPI Server and Node.js
```python
uvicorn main:app --reload
```
in a separate terminal but same directory run:
```python
node server.js
```

The app should be running on: 
**http://127.0.0.1:8000**

## **3. Install Fronted**
### Navigate to frontend folder
```bash
cd ../frontend
```
# Install Dependencies
```bash
npm install
```
# Start React App
```python
npm start
```

The app should be running on: 
**http://localhost:3000**

