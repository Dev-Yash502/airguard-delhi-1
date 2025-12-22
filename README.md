# AirGuard Delhi

AirGuard Delhi is a lightweight AI-powered web application designed to raise awareness about air pollution across different areas of Delhi.

The application allows users to select their local area and instantly view the air quality status (Safe, Moderate, or Dangerous) along with personalized health and safety suggestions. The goal of the project is to reduce the health impact of air pollution using clear visualization and smart, area-specific guidance.

---

## 🚩 Problem Statement
Delhi experiences severe air pollution that varies significantly by location and time. Most citizens lack access to simple, localized, and actionable information about air quality and the precautions they should take in their daily lives.

---

## 💡 Our Solution
AirGuard Delhi provides:
- Area-wise air quality awareness within Delhi
- Color-coded AQI status (Green / Yellow / Red)
- Personalized health and safety recommendations
- A clean, user-friendly interface for quick understanding

The solution focuses on **Prediction, Prevention, and Protection** to help users make informed decisions.

---

## ✨ Key Features
- Multiple Delhi area support
- Visual air quality risk indicators
- Human-friendly health suggestions
- Mobile-first, responsive UI
- Lightweight backend logic for fast response

## 🛠️ Tech Stack

### Frontend
- HTML
- Tailwind CSS
- JavaScript

### Backend
- Python
- Flask

---

## 🤖 AI Tools & Logic Used
- Rule-based decision system for AQI categorization
- Predictive and conditional logic to generate safety suggestions
- AI-driven decision-making approach (logic-based for MVP)

---

## 🌐 Google Technologies Used

- Google Charts – Used to visualize Air Quality Index (AQI) data in graphical form for better user understanding.
- Google Maps Platform (Planned) – To enable location-based AQI mapping and automatic area detection.
- Google Public Data APIs (Planned) – For fetching real-time air quality and environmental data.
---

## 🚀 MVP Deployment
- Frontend deployed on **Netlify**  
  🔗 **Live MVP:** - https://magical-cat-c6c226.netlify.app/
- Backend demonstrated locally for MVP
- Demo video uploaded on **YouTube (Unlisted/Public)**

---

## How to Run the Backend

The backend of AirGuard Delhi is built using Python and Flask and runs locally on the system for MVP demonstration.

First, make sure Python 3 and pip are installed on your machine. Open a terminal or command prompt and navigate to the project directory. Then move into the backend folder by running `cd backend`.

Install the required dependencies by running `pip install flask flask-cors`. This step is required only once. If the terminal shows “Requirement already satisfied”, it means the dependencies are already installed.

After installing the dependencies, start the backend server by running `python app.py`. If the backend starts successfully, the terminal will display the message: `Running on http://127.0.0.1:5000/`.

Once the server is running, open a web browser and test the backend API by visiting any of the following URLs:
`http://127.0.0.1:5000/predict?area=Anand Vihar`,
`http://127.0.0.1:5000/predict?area=Dwarka`,
`http://127.0.0.1:5000/predict?area=Rohini`,
`http://127.0.0.1:5000/predict?area=South Delhi`,
or `http://127.0.0.1:5000/predict?area=North Delhi`.

The API will return a JSON response containing the selected area, AQI value, air quality category (Green, Yellow, or Red), and corresponding health and safety suggestions.

The backend is demonstrated locally for the MVP and is not deployed online. The frontend is deployed separately on Netlify and showcased through the live MVP link.
