\# 🌿 Sugarcane Disease Detection \& Severity Analysis



\## 📌 Overview

This project presents a \*\*Multi-Model Deep Learning System\*\* for automatic detection of sugarcane leaf diseases and their severity analysis.



The system integrates:

\- \*\*MobileNetV3\*\* for disease classification

\- \*\*DeepLabV3\*\* for pixel-level segmentation



Unlike traditional methods, this system not only detects the disease but also \*\*calculates the severity based on infected leaf area\*\*, helping in better agricultural decision-making.



\---



\## 🚀 Key Features

\- ✅ Automatic disease classification  

\- ✅ Pixel-level segmentation of infected regions  

\- ✅ Severity estimation (Mild / Moderate / Severe)  

\- ✅ Real-time prediction capability  

\- ✅ Web-based interface (Frontend + Backend integration)  



\---



\## 🧠 Tech Stack



\### Frontend

\- React.js  

\- HTML  

\- CSS  

\- JavaScript  



\### Backend

\- Python  

\- Flask / FastAPI  



\### Machine Learning

\- PyTorch / TensorFlow  

\- MobileNetV3 (Classification)  

\- DeepLabV3 (Segmentation)  



\---



\## 📂 Project Structure





sugarcane-project/

│

├── frontend/ # React Application (UI)

├── backend/ # API + ML Models

├── .gitmodules # Submodule configuration

└── README.md





\---



\## ⚙️ Installation \& Setup



\### 1️⃣ Clone Repository (with submodules)



```bash

git clone --recurse-submodules https://github.com/loki-4445/sugarcane-project.git

cd sugarcane-project

2️⃣ Setup Backend

cd backend

pip install -r requirements.txt

python app.py

3️⃣ Setup Frontend

cd frontend

npm install

npm start

🔄 System Workflow

User uploads a sugarcane leaf image

Image is preprocessed (resize + normalization)

MobileNetV3 classifies disease

DeepLabV3 segments infected regions

Infected pixels are calculated

Severity is determined:

0–25% → Mild

26–50% → Moderate

>50% → Severe

Final result is displayed to the user

📊 Model Details

🔹 MobileNetV3 (Classification)

Lightweight CNN architecture

Fast and efficient

Extracts features like texture, color, patterns

🔹 DeepLabV3 (Segmentation)

Semantic segmentation model

Uses atrous convolution \& ASPP

Identifies infected regions at pixel level

📈 Performance

✅ \~94% Classification Accuracy

✅ Reliable Severity Estimation

✅ Works on real-world field images

🎯 Applications

Smart Agriculture Systems

Crop Health Monitoring

Farmer Decision Support

Precision Farming

⚠️ Limitations

Limited dataset size

Performance depends on image quality

Sensitive to lighting variations

🔮 Future Enhancements

Mobile application deployment

Multi-crop disease detection

Real-time camera integration

Larger dataset for improved accuracy

👨‍💻 Authors

G. Lokesh

G. Rani

A. Mrudula

G. Subhash

👩‍🏫 Guided By

Dr. A. Madhuri

