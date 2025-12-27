🎤🖥️ Voice Assistant with Vision

A powerful AI voice assistant that can listen, speak, and see your screen — bringing together voice commands, screenshots, and AI reasoning into one seamless experience.

✨ Features

🎙 Voice Interaction
Talk naturally to the assistant — ask questions, give commands, and receive spoken responses.

🖼 Screenshot Capture
Press F9 anytime to capture your screen. The image is sent to the assistant for visual analysis.

🔊 Text-to-Speech
All AI responses are spoken back to you using a built-in TTS engine.

👁 Vision-Powered AI
The assistant can analyze screenshots and use what it sees to help answer questions.

🛠 Installation
📋 Prerequisites

Make sure you have:

Python 3.8+

An OpenAI API Key
Get one from 👉 https://platform.openai.com

🚀 Setup Steps

1️⃣ Clone the repository
git clone https://github.com/n00gy/Voice_Assistant_With_Vision.git

2️⃣ Enter the project folder
cd Voice_Assistant_With_Vision

3️⃣ Create a virtual environment (recommended)
python -m venv venv


Activate it:

Windows

venv\Scripts\activate


Mac / Linux

source venv/bin/activate

4️⃣ Install dependencies
pip install -r requirements.txt

5️⃣ Set your OpenAI API Key

Windows

set OPENAI_API_KEY=your_openai_api_key


Mac / Linux

export OPENAI_API_KEY="your_openai_api_key"

▶️ Usage

Start the assistant:

python main.py

🗣 How to Use

🎤 Speak when prompted to give commands
🖼 Press F9 to take a screenshot
🧠 The assistant will analyze what it sees
🔊 It will reply with voice
❌ Say “exit” or “quit” to stop

📦 Dependencies

This project uses:

Library	Purpose
openai	AI responses
pyttsx3	Text-to-speech
SpeechRecognition	Voice input
keyboard	F9 key detection
Pillow	Screenshot capture
🤝 Contributing

📜 License

This project is licensed under the MIT License — free to use, modify, and distribute.

💙 Acknowledgments

OpenAI for the incredible AI models

Python community for the amazing open-source libraries
