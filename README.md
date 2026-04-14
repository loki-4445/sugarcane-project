# 🌿 Sugarcane Disease Detection & Severity Analysis

## 📌 Overview
This project presents a Multi-Model Deep Learning System for automatic detection of sugarcane leaf diseases and their severity analysis.

The system integrates:
- MobileNetV3 for disease classification
- DeepLabV3 for pixel-level segmentation

Unlike traditional methods, this system not only detects the disease but also calculates the severity based on infected leaf area.

---

## 🚀 Key Features
- Automatic disease classification  
- Pixel-level segmentation  
- Severity estimation (Mild / Moderate / Severe)  
- Real-time prediction  
- Web-based system  

---

## 🧠 Tech Stack

Frontend:
- React.js
- HTML, CSS, JavaScript

Backend:
- Python
- Flask / FastAPI

Machine Learning:
- PyTorch / TensorFlow
- MobileNetV3
- DeepLabV3

---

## 📂 Project Structure

sugarcane-project/
│
├── frontend/
├── backend/
├── .gitmodules
└── README.md

---

## ⚙️ Setup

Clone repo:
git clone --recurse-submodules https://github.com/loki-4445/sugarcane-project.git
cd sugarcane-project

Backend:
cd backend
pip install -r requirements.txt
python app.py

Frontend:
cd frontend
npm install
npm start

---

## 🔄 Workflow
1. Upload leaf image  
2. Preprocess image  
3. Classify using MobileNetV3  
4. Segment using DeepLabV3  
5. Calculate infected area  
6. Predict severity:
   0–25% → Mild  
   26–50% → Moderate  
   >50% → Severe  
7. Show result  

---

## 📊 Performance
- ~94% Accuracy  
- Reliable severity detection  

---

## 🎯 Applications
- Smart agriculture  
- Crop monitoring  
- Farmer assistance  

---

## ⚠️ Limitations
- Depends on dataset  
- Sensitive to image quality  

---

## 🔮 Future Work
- Mobile app  
- Multi-crop support  
- Real-time camera  

---

## 👨‍💻 Authors
- G. Lokesh  
- G. Rani  
- A. Mrudula  
- G. Subhash  

## 👩‍🏫 Guided By
- Dr. A. Madhuri  

---

## 📜 License
For academic and research use only.
