# 🤖 Advanced AI Chatbot

## 📌 Overview
This is an advanced AI-powered chatbot built using **Rasa**, designed to handle both **voice and text input** while providing **responses in voice and text**. It supports **offline functionality** and integrates various **APIs** to enhance features.

## 🚀 Features
✅ Accepts **voice and text input**  
✅ Provides **voice and text responses**  
✅ **Offline mode** for smooth operation without internet  
✅ API integration for extended functionalities  
✅ Context-aware conversational ability  

## 🛠️ Tech Stack
- **Backend:** Rasa (NLP, Dialog Management)
- **Frontend:** Streamlit / JS
- **Speech Processing:** Google Speech-to-Text, Text-to-Speech (TTS)
- **API Integration:** Weather API, T, Custom APIs
  

## 📂 Project Structure
```
📁 chatbot-project
│── 📁 actions/             # Custom actions & API integrations
│── 📁 data/                # Training data (nlu.yml, stories.yml)
│── 📁 models/              # Trained Rasa models
│── 📁 config/              # Configuration files
│── 📁 custom_modules/      # Additional scripts for speech processing
│── 📄 domain.yml           # Define intents, entities, slots
│── 📄 credentials.yml      # API credentials
│── 📄 endpoints.yml        # Server endpoints
│── 📄 config.yml           # Pipeline and policies
│── README.md              # Documentation (this file)
```

## 🚀 Setup & Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/chatbot-project.git
cd chatbot-project
```
### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Train the Model
```bash
rasa train
```
### 5️⃣ Run the Chatbot
```bash
rasa run --enable-api
```
### 6️⃣ Run the Action Server
```bash
rasa run actions
```
### 7️⃣ Test the Chatbot
```bash
rasa shell
```

## 🌐 API Integrations
| Feature | API Used |
|---------|---------|
| Weather Updates | OpenWeather API |
| Text-to-Speech | Google TTS |
| Custom API Calls | RESTful APIs |


## 📜 License
This project is licensed under the **MIT License**.

## 💡 Future Improvements
- **Multilingual Support**
- **More API Integrations**
- **Enhanced Offline Capabilities**
- **Cloud Deployment**

---

🚀 **Developed by Rijul Pimpale 
