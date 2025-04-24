# 🚨 AI-Powered Accident Detection System 

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/UI-Streamlit-FF4B4B)](https://streamlit.io/)

An intelligent system that **detects accidents in images** using AI and triggers emergency responses. Designed for smart cities, traffic monitoring, and rapid emergency coordination.

## 🌟 Key Features:

- **AI Accident Detection**  
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fbrandlogo.org%2Fwp-content%2Fuploads%2F2024%2F06%2FGemini-Icon.png&f=1&nofb=1&ipt=95183a08399342b24a19c8f7b04abb6613908097fda12be47d33fe7f0cd75e52" width="20" alt="Gemini"> Powered by Google's Gemini API
- **Emergency Coordination**  
  <img src="https://img.icons8.com/color/48/google-maps-new.png" width="20" alt="Maps"> Finds nearest hospitals via Google Places API
- **Instant Alerts**  
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcreazilla-store.fra1.digitaloceanspaces.com%2Ficons%2F3254468%2Ftwilio-icon-icon-md.png&f=1&nofb=1&ipt=8730f679afa97030006d86ce30a7bebb64f22eaa6ab3488885ce8ac9f2f3f047" width="20" alt="Twilio"> SMS notifications via Twilio
- **Privacy-First**  
  <img src="https://img.icons8.com/color/48/security-checked.png" width="20" alt="Security"> Auto-deletes images after processing

## 🛠️ Tech Stack:

| Component               | Technology                                                                 |
|-------------------------|----------------------------------------------------------------------------|
| **AI Engine**           | Google Gemini API                                                          |
| **Hospital Lookup**     | Google Places API                                                          |
| **SMS Service**         | Twilio                                                                     |
| **Web Interface**       | Streamlit                                                                  |
| **Core Language**       | Python 3.8+                                                                |
| **Configuration**       | TOML + `.env`                                                              |

**Dependencies:**  
```plaintext
streamlit==1.31.1
Pillow==10.2.0
python-dotenv==1.0.0
twilio==8.3.0
langchain==0.1.11
langchain-google-genai==0.0.11
pydantic==2.6.1
```
## Quick Start:

**Prerequisites**
- Python 3.8+
- API Keys:
  - Google Gemini API
  - Google Places API
  - Twilio Account
 
### Installation:
```Plaintext
# Create virtual environment
python -m venv venv
```
```
# Activate environment
# Linux/macOS:
source venv/bin/activate
# Windows:
.\venv\Scripts\activate
```
```
# Install dependencies
pip install -r requirements.txt
```

### Usage:
```
streamlit run app.py
```

## Project Structure:
```plaintext
accident_detection_app/
├── config/
│   ├── __init__.py
│   └── config_manager.py
├── services/
│   ├── accident_detector.py
│   ├── hospital_service.py
│   └── sms_service.py
├── .env
├── config.toml
├── app.py
└── requirements.txt
```
