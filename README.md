# 🚨 AI-Powered Accident Detection System 

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/UI-Streamlit-FF4B4B)](https://streamlit.io/)

An intelligent system that **detects accidents in images** using AI and triggers emergency responses. Designed for smart cities, traffic monitoring, and rapid emergency coordination.

<img src="https://via.placeholder.com/1200x500.png?text=Accident+Detection+Workflow+Demo" width="800" alt="Workflow Demo">  
*(Replace with actual screenshot/video)*

## 🌟 Key Features

- **AI Accident Detection**  
  <img src="https://img.icons8.com/color/48/google-gemini.png" width="20" alt="Gemini"> Powered by Google's Gemini API
- **Emergency Coordination**  
  <img src="https://img.icons8.com/color/48/google-maps-new.png" width="20" alt="Maps"> Finds nearest hospitals via Google Places API
- **Instant Alerts**  
  <img src="https://img.icons8.com/color/48/twilio.png" width="20" alt="Twilio"> SMS notifications via Twilio
- **Privacy-First**  
  <img src="https://img.icons8.com/color/48/security-checked.png" width="20" alt="Security"> Auto-deletes images after processing

## 🛠️ Tech Stack

| Component               | Technology                                                                 |
|-------------------------|----------------------------------------------------------------------------|
| **AI Engine**           | Google Gemini API                                                          |
| **Hospital Lookup**     | Google Places API                                                          |
| **SMS Service**         | Twilio                                                                     |
| **Web Interface**       | Streamlit                                                                  |
| **Core Language**       | Python 3.8+                                                                |
| **Configuration**       | TOML + `.env`                                                              |

**Dependencies**  
```plaintext
streamlit==1.31.1
Pillow==10.2.0
python-dotenv==1.0.0
twilio==8.3.0
langchain==0.1.11
langchain-google-genai==0.0.11
pydantic==2.6.1
