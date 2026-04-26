# Real-Time Sign Language Interpreter with Speech Output

## 📌 Overview

A real-time AI system that recognizes American Sign Language (A–Z) gestures using a webcam and converts them into text and speech. Designed to improve accessibility for communication between hearing-impaired and non-sign language users.

---

## 🚀 Features

* Real-time hand gesture detection using webcam
* CNN-based classification of ASL alphabets (A–Z)
* Converts gestures into words and sentences
* Auto-suggestion for faster word formation
* Text-to-speech output for audio communication

---

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe
* CNN (Keras / TensorFlow)
* Tkinter
* pyttsx3

---

## 📂 Project Structure

```
sign_lang/
│
├── main.py
├── white.jpg
├── .gitignore
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/n-varsha13/sign-language-interpreter-cnn.git
```

2. Navigate to the project folder:

```
cd sign-language-interpreter-cnn/sign_lang
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the project:

```
python main.py
```

---

## 📊 Dataset

The dataset consists of ASL alphabet images (A–Z).
Due to size limitations, it is not included in this repository.

---

## 🔊 Output

* Displays predicted alphabets on screen
* Forms words and sentences
* Converts output text into speech

---

## 📌 Future Improvements

* Support for dynamic gestures (words instead of alphabets)
* Improved accuracy under varying lighting conditions
* Deployment as a web/mobile application

---

## 👩‍💻 Author

Varsha N
