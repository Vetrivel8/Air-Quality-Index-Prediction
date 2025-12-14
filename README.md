# 🌍 BREATHESAFE – AI-Powered Air Quality Forecasting Platform

BREATHESAFE is a dual-platform AI system that predicts and monitors Air Quality Index (AQI) levels using machine learning models and a modern web interface, helping users make informed health and environmental decisions.

---

## 📌 Overview

BREATHESAFE combines a Python-based machine learning backend with a Next.js web application to provide real-time air quality monitoring and 24-hour AQI forecasting. The platform supports multiple cities, visual dashboards, and health recommendations based on pollution levels.

---

## 🏗️ Architecture

The project consists of two major components:

### 1️⃣ Python ML Backend
- Synthetic AQI dataset generation
- Data preprocessing and feature engineering
- Random Forest model for fast predictions
- LSTM model for time-series AQI forecasting
- Model evaluation with metrics and visualizations
- 24-hour AQI forecasting engine
- REST API using FastAPI
- Interactive dashboard using Streamlit

### 2️⃣ Next.js Web Application
- Modern, eco-conscious landing page
- Interactive AQI dashboard
- Multi-city air quality monitoring
- Responsive, mobile-first design
- API integration for real-time predictions

---

## ✨ Key Features

### Data & Predictions
- AQI prediction for 6 pollutants (PM2.5, PM10, NO₂, SO₂, CO, O₃)
- Weather-based forecasting using 5 parameters
- AQI categorization with health recommendations
- Confidence-aware predictions

### Web Interface
- Live AQI dashboard with charts
- City selection and real-time updates
- Educational problem–solution flow
- Smooth animations and dark-theme UI
- Newsletter signup and contact forms

### API Endpoints
- `POST /predict` – AQI prediction from current conditions  
- `POST /forecast` – 24-hour AQI forecast  
- `GET /health/{aqi}` – Health recommendations  
- `GET /status` – API health check  

---

## 🛠️ Tech Stack

### Frontend
- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS v4
- shadcn/ui
- Recharts
- Lucide React

### Backend (ML)
- Python
- NumPy, Pandas
- Scikit-learn
- TensorFlow / Keras
- FastAPI
- Streamlit

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- Python 3.9+
- npm or yarn

### Web Application Setup
```bash
git clone https://github.com/your-username/breathesafe.git
cd breathesafe/web
npm install
npm run dev
