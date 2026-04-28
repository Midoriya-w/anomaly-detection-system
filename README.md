# 🔍 Visual Anomaly Detection System

## 📌 Overview
This project presents an AI-based anomaly detection system for identifying defects in images without requiring labeled defect data. The system uses deep learning techniques to learn normal patterns and detect deviations.

## 🚀 Features
- Detects defects without labeled datasets
- Generates anomaly heatmaps
- Provides anomaly score
- Real-time image analysis
- Simple UI using Streamlit

## 🧠 Model Used
- Pre-trained CNN (Feature Extraction)
- PaDiM (Patch Distribution Modeling) for anomaly detection

## ⚙️ Tech Stack
- Python
- PyTorch
- OpenCV
- Anomalib
- Streamlit

## 🔄 How It Works
1. User uploads an image  
2. Image is preprocessed  
3. CNN extracts features  
4. PaDiM models normal feature distribution  
5. System computes anomaly score  
6. Heatmap highlights defective regions  

## 📸 Output Example

## ▶️ Run the Project
bash
pip install -r requirements.txt
streamlit run app.py

## 📂 Project Structure
project
 ├── app.py
 ├── model
 ├── utils
 ├── images
 ├── requirements.txt
 └── README.md
