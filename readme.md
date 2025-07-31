# 🎙️ Speech to Text Converter using Python

This project is a simple speech recognition tool that takes microphone input and converts it to text using Google's speech recognition API.

## 📌 Features

- 🎤 Capture audio from microphone
- 🔊 Convert speech to text using `speech_recognition`
- 👩‍💻 Prints the transcribed text to the console
- 🧑‍🎓 Beginner-friendly and easy to extend

---

## 📂 Project Structure

```
SpeechToText/
│
├── speech_to_text.py   # Main Python script
└── README.md           # Project documentation
```

---

## 🛠️ Requirements

Make sure Python is installed (Python 3.6+ recommended)

### Install required libraries:

```bash
pip install SpeechRecognition
pip install pyttsx3
pip install pyaudio
```

> ⚠️ If you face issues installing `pyaudio`, try this:
>
> ```bash
> pip install pipwin
> pipwin install pyaudio
> ```

---

## 💡 How to Use

1. Connect a working microphone.
2. Run the script:

```bash
python speech_to_text.py
```

3. Speak when prompted.
4. The program will print your speech as text.

---

## 📜 Example Output

```
say something.....
done!
you said Hello, how are you?
```