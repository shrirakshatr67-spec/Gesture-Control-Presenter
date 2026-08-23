#🖐️ Gesture Control Presenter


A Python-based computer vision application that allows users to control Google Slides presentations using real-time hand gestures through a laptop webcam.

The system detects hand landmarks using MediaPipe, processes the webcam feed using OpenCV, recognizes predefined gestures, and uses PyAutoGUI to perform presentation controls automatically.

#🎥 Project Demo

A demonstration of the project is available in my LinkedIn project post:

[https://lnkd.in/p/g4jwefB9]

The demo shows how different hand gestures can be used to control a Google Slides presentation without touching the keyboard or mouse.

#✨ Features
🖐️ Hands-free Google Slides control
📷 Real-time webcam-based hand tracking
🤖 AI-powered hand landmark detection
👆 Gesture recognition
⌨️ Automated keyboard control
💻 Works with a laptop webcam
🔌 No additional hardware required
⚡ Real-time gesture processing
🧠 Gesture Controls

#Gesture	Action
✋ Open Palm	Next Slide
🤟 Three Fingers	Previous Slide
✌️ Two Fingers	Start Slideshow
✊ Fist	Exit Slideshow

#🛠️ Technologies Used
Python
OpenCV – Webcam capture and image processing
MediaPipe – Hand landmark detection
PyAutoGUI – Keyboard automation
Computer Vision
Hand Gesture Recognition

#⚙️ How It Works
The application follows this workflow:

Laptop Webcam
      ↓
   OpenCV
      ↓
MediaPipe Hand Detection
      ↓
Hand Landmark Detection
      ↓
Finger Position Analysis
      ↓
Gesture Recognition
      ↓
Gesture-to-Keyboard Mapping
      ↓
     PyAutoGUI
      ↓
 Google Slides Control
 
#Processing Steps
The laptop webcam captures the user's hand movements.
OpenCV processes the real-time camera frames.
MediaPipe detects the hand and identifies its landmarks.
The application analyzes finger positions.
Recognized gestures are mapped to presentation actions.
PyAutoGUI sends the corresponding keyboard commands.
Google Slides responds to the commands and changes the presentation.

#🚀 Installation
#Prerequisites
Make sure you have:

Python 3 installed
A working laptop/USB webcam
Google Chrome
A Google Slides presentation
Check your Python installation:

python --version
#1. Clone the Repository
Clone this repository using Git:

https://github.com/shrirakshatr67-spec/Gesture-Control-Presenter.git
Move into the project directory:

cd gesture-control-presenter
#2. Create a Virtual Environment
For Windows:

python -m venv .venv
Activate the virtual environment:

.venv\Scripts\activate
After activation, your terminal should show:

(.venv)
#3. Install Dependencies
Install the required Python packages:

pip install -r requirements.txt
#4. Download the Hand Landmarker Model
Run:

python setup_models.py
This downloads the required MediaPipe hand landmark model used by the application.

#▶️ Running the Application
Start the application using:

python main.py
Allow the application to access your webcam if Windows asks for permission.

#🎯 How to Use
Open your Google Slides presentation in Google Chrome.
Start the presentation/slideshow.
Make sure your webcam is working.
Run the Python application.
Position your hand clearly in front of the webcam.
Perform the supported gestures.
The application will recognize the gesture and control the presentation.
#📂 Project Structure
gesture-control-presenter/
│
├── .gitignore
├── README.md
├── main.py
├── requirements.txt
└── setup_models.py
The MediaPipe model is downloaded separately by setup_models.py and should not need to be committed to the Git repository.

#📦 Dependencies
The project uses:

mediapipe==0.10.35
opencv-python>=4.8.0
pyautogui>=0.9.54
These dependencies are listed in:

requirements.txt
Install them using:

pip install -r requirements.txt

#🧩 Key Concepts Demonstrated
This project demonstrates practical implementation of:

Computer Vision
Hand Landmark Detection
Gesture Recognition
Real-Time Webcam Processing
Human-Computer Interaction (HCI)
Python Automation
Keyboard Event Automation

#🔮 Future Improvements
Possible future enhancements include:

👉 Swipe gesture recognition
🔴 Gesture-based laser pointer
🔊 Volume control using gestures
🔍 Zoom control using hand gestures
✋ Multi-hand gesture support
🧠 Custom gesture training
🎨 Improved gesture visualization
⚡ Better gesture stability and noise reduction

#⚠️ Important Notes
For better gesture recognition:

Ensure sufficient lighting.
Keep your hand clearly visible to the webcam.
Avoid heavily cluttered backgrounds.
Keep your hand at a moderate distance from the camera.
Make gestures clearly and hold them briefly when necessary.

#🎓 Learning Outcomes
Through this project, I gained practical experience with:

Python programming
OpenCV
MediaPipe
Computer Vision
Real-time image processing
Hand landmark detection
Gesture recognition
Python automation
Human-computer interaction

#👨‍💻 Author
Shriraksha T R

Engineering Student | Python | Computer Vision | Software Development

#⭐ Project
If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.
# 🖐️ Gesture Control Presenter

A Python-based **computer vision application** that allows users to control Google Slides presentations using real-time hand gestures through a laptop webcam.

The system detects hand landmarks using **MediaPipe**, processes the webcam feed using **OpenCV**, recognizes predefined gestures, and uses **PyAutoGUI** to perform presentation controls automatically.

---

## 🎥 Project Demo

A demonstration of the project is available in my LinkedIn project post:

**[https://lnkd.in/p/gEpzfEWh]**

The demo shows how different hand gestures can be used to control a Google Slides presentation without touching the keyboard or mouse.

---

## ✨ Features

* 🖐️ Hands-free Google Slides control
* 📷 Real-time webcam-based hand tracking
* 🤖 AI-powered hand landmark detection
* 👆 Gesture recognition
* ⌨️ Automated keyboard control
* 💻 Works with a laptop webcam
* 🔌 No additional hardware required
* ⚡ Real-time gesture processing

---

## 🧠 Gesture Controls

| Gesture          | Action          |
| ---------------- | --------------- |
| ✋ Open Palm      | Next Slide      |
| 🤟 Three Fingers | Previous Slide  |
| ✌️ Two Fingers   | Start Slideshow |
| ✊ Fist           | Exit Slideshow  |

---

## 🛠️ Technologies Used

* **Python**
* **OpenCV** – Webcam capture and image processing
* **MediaPipe** – Hand landmark detection
* **PyAutoGUI** – Keyboard automation
* **Computer Vision**
* **Hand Gesture Recognition**

---

## ⚙️ How It Works

The application follows this workflow:

```text
Laptop Webcam
      ↓
   OpenCV
      ↓
MediaPipe Hand Detection
      ↓
Hand Landmark Detection
      ↓
Finger Position Analysis
      ↓
Gesture Recognition
      ↓
Gesture-to-Keyboard Mapping
      ↓
     PyAutoGUI
      ↓
 Google Slides Control
```

### Processing Steps

1. The laptop webcam captures the user's hand movements.
2. OpenCV processes the real-time camera frames.
3. MediaPipe detects the hand and identifies its landmarks.
4. The application analyzes finger positions.
5. Recognized gestures are mapped to presentation actions.
6. PyAutoGUI sends the corresponding keyboard commands.
7. Google Slides responds to the commands and changes the presentation.

---

# 🚀 Installation

## Prerequisites

Make sure you have:

* Python 3 installed
* A working laptop/USB webcam
* Google Chrome
* A Google Slides presentation

Check your Python installation:

```bash
python --version
```

---

## 1. Clone the Repository

Clone this repository using Git:

```bash
https://github.com/Ashmita-bit/gesture-control-presenter.git
```

Move into the project directory:

```bash
cd gesture-control-presenter
```


---

## 2. Create a Virtual Environment

For Windows:

```powershell
python -m venv .venv
```

Activate the virtual environment:

```powershell
.venv\Scripts\activate
```

After activation, your terminal should show:

```text
(.venv)
```

---

## 3. Install Dependencies

Install the required Python packages:

```powershell
pip install -r requirements.txt
```

---

## 4. Download the Hand Landmarker Model

Run:

```powershell
python setup_models.py
```

This downloads the required MediaPipe hand landmark model used by the application.

---

# ▶️ Running the Application

Start the application using:

```powershell
python main.py
```

Allow the application to access your webcam if Windows asks for permission.

---

# 🎯 How to Use

1. Open your Google Slides presentation in Google Chrome.
2. Start the presentation/slideshow.
3. Make sure your webcam is working.
4. Run the Python application.
5. Position your hand clearly in front of the webcam.
6. Perform the supported gestures.
7. The application will recognize the gesture and control the presentation.

---

# 📂 Project Structure

```text
gesture-control-presenter/
│
├── .gitignore
├── README.md
├── main.py
├── requirements.txt
└── setup_models.py
```

The MediaPipe model is downloaded separately by `setup_models.py` and should not need to be committed to the Git repository.

---

# 📦 Dependencies

The project uses:

```text
mediapipe==0.10.35
opencv-python>=4.8.0
pyautogui>=0.9.54
```

These dependencies are listed in:

```text
requirements.txt
```

Install them using:

```powershell
pip install -r requirements.txt
```

---

# 🧩 Key Concepts Demonstrated

This project demonstrates practical implementation of:

* Computer Vision
* Hand Landmark Detection
* Gesture Recognition
* Real-Time Webcam Processing
* Human-Computer Interaction (HCI)
* Python Automation
* Keyboard Event Automation

---

# 🔮 Future Improvements

Possible future enhancements include:

* 👉 Swipe gesture recognition
* 🔴 Gesture-based laser pointer
* 🔊 Volume control using gestures
* 🔍 Zoom control using hand gestures
* ✋ Multi-hand gesture support
* 🧠 Custom gesture training
* 🎨 Improved gesture visualization
* ⚡ Better gesture stability and noise reduction

---

# ⚠️ Important Notes

For better gesture recognition:

* Ensure sufficient lighting.
* Keep your hand clearly visible to the webcam.
* Avoid heavily cluttered backgrounds.
* Keep your hand at a moderate distance from the camera.
* Make gestures clearly and hold them briefly when necessary.

---

# 🎓 Learning Outcomes

Through this project, I gained practical experience with:

* Python programming
* OpenCV
* MediaPipe
* Computer Vision
* Real-time image processing
* Hand landmark detection
* Gesture recognition
* Python automation
* Human-computer interaction

---

# 👨‍💻 Author

**Ashmita Vijapur**

Engineering Student | Python | Computer Vision | Software Development

---

## ⭐ Project

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.
