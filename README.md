# 👁️ NzubeGlaucoDetect AI

**AI-powered glaucoma screening tool with integrated ophthalmology chatbot**

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://glaucodetect.streamlit.app)
![Python](https://img.shields.io/badge/Python-3.11%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.16-orange)

## 📌 Overview
A Streamlit web application that:
- Detects glaucoma from fundus images using deep learning
- Features an AI chatbot (Groq/Llama) for ophthalmology Q&A
- Maintains patient records and prediction history
- Secure user authentication system

## 🛠️ Tech Stack
| Component | Technology |
|-----------|------------|
| Frontend | Streamlit |
| AI Model | TensorFlow/Keras |
| Chatbot | Groq API (Llama-4-scout-17b) |
| Database | SQLite (PostgreSQL-ready) |
| Auth | SHA-256 hashing |

## 📂 Project Structure
NzubeGlaucoDetect-AI/
├── .streamlit/
│ ├── config.toml # UI configuration
│ └── secrets.toml # API keys (not committed)
├── app.py # Main application
├── NzubeGlaucoma_AI_Predictor.h5 # Trained model
├── requirements.txt # Dependencies
├── logo.png # Brand logo
└── users.db # Database (ignored in Git)

## ✨ Key Features
- **Dual-eye analysis**: Separate uploads for left/right eyes
- **Medical chatbot**: Real-time streaming responses
- **Patient records**: Stores IOP, demographics, and results
- **Responsive UI**: Mobile-friendly interface

## 🔧 Requirements
streamlit>=1.32.0
tensorflow>=2.16.1
groq>=0.3.0
pillow>=10.2.0

## 📝 Usage Guide
Login/Signup

Upload Fundus Images

Right and left eyes separately

Include IOP measurements

Chat with AI
Ask about:

Glaucoma symptoms

Treatment options

Prevention tips

⚠️ Disclaimer
This tool is for educational purposes only. Always consult a qualified ophthalmologist for medical diagnosis.

### 📄 License
MIT © 2025 Dr. Anthony Nzubechukwu Anyanwu
