# AgroAI 🌾

AgroAI is an Artificial Intelligence (AI) and Internet of Things (IoT)-inspired crop recommendation system built as a **proof-of-concept** to assist smallholder farmers in Lesotho. By combining environmental sensor readings and machine learning, AgroAI aims to offer intelligent, real-time crop guidance and agricultural advice to boost yield and enhance decision-making in agriculture.

> ⚠️ **Disclaimer:** This repository contains code and documentation created as part of a final year B.Sc. Computer Science project at the **National University of Lesotho**. Ownership and use of this material are subject to the university's academic policies. Authors do not claim full or exclusive rights over the contents.

---

## 📚 Project Overview

AgroAI simulates an end-to-end smart agriculture solution that:

- Accepts soil nutrient data and climate parameters (N, P, K, pH, temperature, humidity, rainfall)
- Uses a **Random Forest** machine learning model to recommend optimal crops
- Provides additional advice for custom crop selections using a rule-based expert system
- Stores all user and field data in a PostgreSQL database
- Displays results in a responsive, interactive **web dashboard** built with JavaScript (Leaflet.js, Chart.js)

---

## 💡 Motivation

Lesotho’s agricultural sector faces challenges including:

- Climate change
- Low crop yields
- Reliance on traditional, outdated farming techniques

AgroAI was built to explore how **AI and IoT** can empower smallholder farmers with real-time, actionable insights and transform agriculture into a more resilient and sustainable sector.

---

## 🛠️ System Architecture

AgroAI consists of:

- **Frontend:** JavaScript + HTML/CSS, Leaflet.js for field mapping, Chart.js for visualizing environmental data
- **Backend:** FastAPI (Python) for model inference and API endpoints
- **Expert System:** Rule-based advisory module using agronomic thresholds
- -**Artificial Intelligence Model:** A model used to recommend crops to farmers based on their envirronment data.
- **Database:** PostgreSQL for storing sensor data, user info, recommendations, and crop tracking

---

## 🔬 Machine Learning

- **Model:** Random Forest Classifier
- **Training Data:** Kaggle Crop Recommendation Dataset
- **Accuracy:** ~97.40% on test data
- **Model Input:** Simulated environmental sensor values
- **Model Output:** Best crop to grow under the given conditions

---

## 📈 Features

- 🔍 Real-time crop recommendation
- 📊 Graphs for sensor data tracking
- 🧠 Rule-based advice for alternative crops
- 📍 Field mapping using Leaflet.js
- 👨‍🌾 Crop tracking from seeding to harvest
- 🗃️ Simulated IoT sensor values for testing

---

## 🧪 Testing and Evaluation

- ✅ Unit Testing: Core modules (model, expert system, API)
- ✅ Integration Testing: Frontend ↔ Backend ↔ Database
- ✅ System Testing: Full application under simulated real-world scenarios

---

## 📦 How to Run (Dev Mode)

> This version assumes simulated sensors and is for academic demonstration only.

1. **Backend**  
   - Install dependencies: `pip install -r requirements.txt`
   - Run FastAPI server: `uvicorn main:app --reload`
   - Run Flask server: `python app,py`

2. **Frontend**  
   - Open `ilandingpage.html` in your browser
   - Simulate sensor readings and view recommendations

3. **Database**  
   - Set up PostgreSQL using provided schema
   - Ensure connection credentials match backend config

---

## 🧠 Future Enhancements

- Integration with physical IoT sensor hardware
- Mobile app with offline-first architecture
- Multilingual support (e.g., Sesotho)
- Real-time data syncing and harvest outcome feedback loops
- Secure user authentication and role management

---

## 🏛️ Academic Details

**Title:** AgroAI – An Artificial Intelligence Driven Crop Recommendation Proof-of-Concept for Lesotho  
**Authors:** Tlotliso Khosi (202100017) and Keketso Tolo (202100092)  
**Supervisor:** Mx. Mathe Ntšekhe  
**Co-supervisor:** Dr. Lerato Lerato  
**Institution:** National University of Lesotho, Department of Mathematics and Computer Science  
**Year:** May 2025

---

## 📄 License and Ownership

This project was developed as part of an academic requirement. The authors **do not claim full or commercial ownership** of the work. Reuse or adaptation of this repository is permitted for **educational and non-commercial purposes only**, with proper attribution.

---

## 🙏 Acknowledgements

- Mx. Mathe Ntšekhe and Dr. Lerato Lerato – for supervision and guidance
- Ms. Moipone Sebitia – for agricultural domain expertise
- Farmers and students who contributed through feedback and surveys

---

## 🌍 Vision

AgroAI envisions a future where smallholder farmers in Lesotho and beyond can access real-time, intelligent agricultural advice to improve yields, combat climate change impacts, and sustain food security through smart, affordable technologies.

