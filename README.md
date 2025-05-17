# 🤖 Jarvis AI Assistant

A desktop voice-controlled assistant built using Python that performs tasks like searching the web, playing music, sending WhatsApp messages, opening apps, checking weather/location, telling jokes, sending emails, and more — just by speaking!

## 🚀 Features

- Voice recognition and speech response
- Play music locally or on YouTube
- Open system apps and websites
- Send WhatsApp messages via automation
- Speak system condition and battery level
- Dictionary support (meaning, synonym, antonym)
- Social media shortcuts
- Fun commands and personalized interaction
- Email functionality using Gmail SMTP
- Tells jokes, current day, temperature, and more

## 🧰 Tech Stack

- **Python 3.x**
- **SpeechRecognition**
- **pyttsx3**
- **pywhatkit**
- **wikipedia**
- **requests**
- **BeautifulSoup**
- **psutil**
- **PyDictionary**
- **keyboard**

## 📁 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/jarvis-assistant.git
   cd jarvis-assistant

2. Install dependencies:
   pip install -r requirements.txt

3. Add your Gmail credentials in idlist.py for email functionality.

4. Run the assistant:
   python main.py

⚠️ Prerequisites
Working microphone

Internet connection (for online features)

Python packages listed in requirements.txt

🧠 Note
All commands are voice-driven.

It will terminate if there is no internet connection at startup.

