# 👁️🖱️ Eye-Controlled Mouse Using OpenCV and IP Camera

## 🔍 Overview

The Eye-Controlled Mouse project is an assistive Human–Computer Interaction (HCI) system that enables users to control the mouse cursor using eye movements 👀.
It leverages computer vision techniques with OpenCV and supports both a built-in webcam 🎥 and a smartphone-based IP camera 📱.

This solution is especially valuable for users with limited mobility, offering a hands-free, accessible input method through real-time eye tracking and blink detection ♿✨.

## ✨ Key Features

- ✅ **Real-time video capture using:**
  - 🎥 Built-in webcam
  - 📱 Smartphone camera via IP camera streaming
- ✅ 👁️ **Eye detection and tracking** using OpenCV
- ✅ ➡️ **Cursor movement** controlled by right eye movement
- ✅ 👈 **Mouse click simulation** via left eye blink detection
- ✅ ⚡ **Low-latency, real-time processing**
- ✅ ⌨️ **Simple keyboard-based termination** (Esc key)

## 🧰 Technology Stack

- 🐍 **Programming Language:** Python 3.x
- 👁️‍🗨️ **Computer Vision:** OpenCV (opencv-python)
- 🎮 **Input Devices:**
  - Built-in webcam
  - Smartphone with IP camera application

## 💻 System Requirements

- ✅ Python 3.7 or higher
- ✅ OpenCV (opencv-python)
- ✅ Stable camera feed (webcam or smartphone IP camera)
- 🖥️ Windows / Linux / macOS
  *(Mouse control behavior may vary based on OS permissions)*

## 📦 Installation

### 🔹 1. Clone the Repository
```bash
git clone https://github.com/vvvvvivekkk/eye_controlled_mouse.git
cd eye_controlled_mouse
```

### 🔹 2. Install Dependencies
```bash
pip install -r requirements.txt
```

## ▶️ Usage

Run the application:

```bash
python main.py
```

🚀 Once launched, the application starts capturing video frames and processes eye movements in real time.

## 🎮 Controls

- 👁️ **Right Eye Movement** → Controls mouse cursor position
- 😉 **Left Eye Blink** → Performs mouse click
- ⛔ **Esc Key** → Safely exits the application

## 🧠 How It Works (High-Level)

1.  **Capture video frames** from the selected camera source
2.  **Detect facial landmarks** and eye regions
3.  **Track eye position** to calculate cursor movement
4.  **Detect blink patterns** for click actions
5.  **Map eye movement** to screen coordinates in real time

## 🛠️ Troubleshooting

- 🔧 Ensure the selected camera is not used by another application
- 📡 Verify the IP camera URL if using a smartphone
- 💡 Maintain proper lighting for accurate eye detection
- 🔄 Reinstall dependencies if OpenCV-related errors occur

## 🚀 Potential Enhancements

- ✨ Scroll gesture support
- 🎯 Calibration mode for improved accuracy
- 🖥️ Multi-monitor support
- 🤖 Deep learning-based eye tracking (MediaPipe / Dlib)
- 🎛️ Custom sensitivity and click thresholds

## 🤝 Contributions

Contributions are welcome and appreciated 🙌

You can:
- 🐞 Open an issue for bug reports or feature requests
- 🔧 Submit a pull request with improvements or enhancements

📌 Please ensure your code follows best practices and includes proper documentation.

## 🙏 Acknowledgments

This project was developed with the goal of enhancing accessibility through assistive technology ♿💙.

## 👏 Credits

- 💐 Special thanks to the OpenCV community for providing powerful computer vision tools.
