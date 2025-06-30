# 🌐 SaraLiveAudioTranslator

**SaraLiveAudioTranslator** is a real-time voice-to-voice translation web app that lets users **speak in one language** and hear or read the **translated output in another** — instantly! This project is built using HTML, CSS, and JavaScript, leveraging browser APIs like **Speech Recognition**, **Text Translation**, and **Speech Synthesis**.

---

## 🚀 Features

- 🎙️ **Live Speech Input** (via microphone)
- 🌐 **Language Translation** (Powered by LibreTranslate or Google Translate API)
- 🔊 **Speech Output** in Target Language
- 📝 Display both **original** and **translated** text
- 📱 Fully responsive UI (mobile-friendly)

---

## 🧪 Demo

[🔗 Live Demo https://liveaudiotranslate.netlify.app]

---

## 🛠️ Technologies Used

| Feature | Technology |
|--------|-------------|
| 🎤 Speech-to-Text | `webkitSpeechRecognition` |
| 🔁 Translation | LibreTranslate API or Google Translate API |
| 🔊 Text-to-Speech | `SpeechSynthesisUtterance` |
| 💻 Frontend | HTML5, CSS3, JavaScript (Vanilla) |

---

## 🧩 How It Works

1. User selects **Source Language** and **Target Language**
2. Clicks on **“Start Talking”**
3. The app captures voice input and converts it to text
4. The captured text is sent to the **translation API**
5. The translated result is:
   - Shown on screen
   - Optionally **read out loud** in the target language

---

## 🔧 Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/SaraLiveAudioTranslator.git
   cd SaraLiveAudioTranslator

2. Open index.html in your browser (no server required)


3. To use translation API, replace the demo endpoint:

Use LibreTranslate or

Use Google Translate API





---

🗂️ Project Structure

SaraLiveAudioTranslator/
├── index.html
├── style.css
├── script.js
├── /assets
│   ├── icons/
│   └── audio/ (optional if using custom audio)
└── README.md


---

🌍 Supported Languages (example)

Bengali (bn)

Tamil (ta)

Hindi (hi)

English (en)

Telugu (te)

Urdu (ur)

Kannada (kn)

Malayalam (ml)


You can expand the language list as needed.


---

📦 Dependencies

No external libraries required. Built using native browser APIs:

webkitSpeechRecognition

fetch for API calls

SpeechSynthesisUtterance



---

🧑‍💻 Author

Sohel Rana
Developer | Electronics & Communication Enthusiast
LinkedIn | YouTube


---

📜 License

This project is licensed under the MIT License


---

🙌 Contributions

Pull requests are welcome! If you’d like to add more language support, improve UI, or integrate a more advanced AI-based translation model – feel free to contribute.


---

💬 Acknowledgements

Google Web Speech API

LibreTranslate Open Source API

Mozilla Developer Docs


---

If you want, I can also help you:
- Host the project on GitHub Pages
- Generate the complete working source code
- Add screenshots and a logo for `SaraLiveAudioTranslator`

Let me know if you'd like that too!

