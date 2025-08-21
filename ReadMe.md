# 🎙️ Speech Transcriber 

A Flask-based web application that converts speech into text using the **SpeechRecognition** library.<br>This project allows users to upload or record audio and receive an accurate text transcription in real time.

## 🚀 Features
- 🎤 Convert speech to text using Python’s speech_recognition library.
- 🌐 Simple Flask web interface.
- 🎨 User-friendly UI with HTML/CSS frontend.
- ⚡ Lightweight and easy to deploy.

## 🛠️ Installation & Setup
1. Clone the repository
```
git clone https://github.com/pereruannabaala/SpeechRecognition.git
```
2. Navigate to the project
```
cd SpeechRecognition
```
3. Create a virtual environment
```
python3 -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate  
```
4. Install dependencies
```
pip install -r requirements.txt
```
5. Run the Flask app
```
flask run
```

## 📂 Project Structure
```
SpeechRecognition/
│── app.py               # Main Flask application
│── requirements.txt     # Dependencies
│── templates/
│   └── index.html       # Frontend template
│── static/css/
│   └── styles.css       # Styling
└── venv/                # Virtual environment (do not push to GitHub)
```

## 🧰 Requirements
- Python 3.8+
- Flask
- SpeechRecognition

## ✨ Future Improvements
- Add real-time transcription with WebSockets.
- Support multiple languages.
- Export transcription as .txt or .docx.

## ✍️ Author
- **Pereruan Nabaala**
- pereruannabaala@gmail.com
