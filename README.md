# 🚗 Drive Safety

## Driver Drowsiness Detection System

A machine learning application designed to detect possible driver drowsiness using eye and mouth analysis.

## 📌 Project Description

The system analyzes a driver's face to detect signs of drowsiness based on:

- 👁️ Eye status
- 👄 Mouth/yawning status
- 🚨 Final drowsiness result

The application provides two input methods:

- 📷 Camera
- 🖼️ Upload Image

## 🛠️ Technologies Used

- Python 3.12
- TensorFlow 2.20.0
- NumPy 2.0.2
- OpenCV 5.0.0.93
- Scikit-learn 1.6.1
- Matplotlib 3.10.0
- Streamlit 1.61.1

## 🤖 Models

The project uses:

- `eye_model_deploy.keras
- `mouth_model.keras
- `face_detection_yunet_2023mar.onnx

## 📂 Project Structure

```text
drive-safety-project/
│
├── README.md
├── app.py
├── requirements.txt
├── eye_model_deploy.keras
├── mouth_model.keras
└── face_detection_yunet_2023mar.onnx
