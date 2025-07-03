
# 🖱️ Gesture-Controlled Virtual Mouse

A Python-based AI system that allows you to control your computer using **hand gestures** via webcam. Built with OpenCV, MediaPipe, PyAutoGUI, and Pycaw, this tool lets you perform mouse actions, adjust system volume/brightness, and scroll — all **touch-free**.


## 🎯 Features

- 🖐️ Real-Time Hand Gesture Recognition using MediaPipe
- 🧠 Gesture Classification with `HandRecog` Class
- 🖱️ Mouse Movement, Clicks, Right-Click, and Drag via Gestures
- 🔊 Control System Volume using Pinch Gestures
- 💡 Adjust Screen Brightness with Gestures
- 🧭 Horizontal & Vertical Scrolling
- 🔄 Smooth gesture transitions with frame stabilization
- 📷 Works with live webcam feed (OpenCV)

## 📁 Project Structure
    
    Gesture Project/
    ├── src/
    │ ├── main.py # Entry script
    │ ├── virtual_mouse.py # Core logic: gesture detection & control
    ├── requirements.txt # All dependencies
    ├── README.md # Project overview (you're here!)


## 🛠️ Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/gesture-controlled-mouse.git
    cd gesture-controlled-mouse/src

2. Install dependencies
    ```bash
    pip install -r ../requirements.txt

3. **Run the project**
    ```bash
    python main.py
    
## 📦 Requirements

Listed in requirements.txt, including:

opencv-python

mediapipe

pyautogui

pycaw

screen-brightness-control

protobuf

comtypes

# 🧠 Gesture Mappings

Gesture	Action

✋ Palm	Idle (no action)
✌️ V-sign	Activate mouse control
👊 Fist	Hold/Drag
☝️ Index Finger	Right Click
✌️ (Closed Fingers)	Double Click
🤏 Pinch (Major)	Brightness / Volume
🤏 Pinch (Minor)	Horizontal/Vertical Scroll

# 🧪 Tested On

Python 3.11+

Windows 10/11

Laptop Webcam

# 📌 Future Improvements

Add GUI overlay for gesture guide

Support for multi-monitor environments

Add voice feedback or click sound

Dark mode camera window

# 👨‍💻 Developed By

Harvinder Kaur

B.Tech Final Year Student

Contact: [harvinderkaur2622@example.com]

GitHub: [https://github.com/harvinderkaur02]

# 📜 License

This project is licensed under the MIT License.
