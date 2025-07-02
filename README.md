🎤 Multilingual Voice Translator

A real-time voice-to-voice language translator built with Python, Streamlit, and Google APIs. This app listens to speech input in one language, translates it into another language using Google Translate, and plays the translated speech using text-to-speech.


🔍 Features

- Real-time voice input using microphone
- Speech-to-text recognition using Google Speech Recognition
- Translation using Google Translate API
- Audio playback using gTTS and pygame
- Streamlit-based user interface
- Supports all languages supported by Google Translate

🛠️ Tech Stack

- Language: Python
- Libraries/Tools:
  - Streamlit  
  - SpeechRecognition  
  - googletrans  
  - gTTS  
  - pygame  

🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Abhirup2004-p/Multilingual-Voice-Translator.git
   cd Multilingual-Voice-Translator


2. Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Run the app:

   ```bash
   streamlit run translator.py



📷 Sample Use Case

* Select source and target languages (e.g., English to Hindi)
* Click **Start**
* Speak into the microphone
* Hear the translated text spoken back in the selected language
* Click **Stop** to end the session


💡 Possible Improvements

* Add option to save transcripts
* Display text output alongside audio
* Add support for regional accents or custom voice models



🤝 Contributing

Pull requests and suggestions are welcome! If you find any bugs or have ideas for improvement, feel free to open an issue.
