# 👁️ Eye Controlled Mouse

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Face%20Mesh-orange?style=for-the-badge&logo=google&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

Control your mouse cursor using just your eyes! 🖱️👀

This application uses computer vision and machine learning to track your eye movements and blink gestures, allowing you to navigate your computer hands-free. Built with **OpenCV**, **MediaPipe**, and **PyAutoGUI**.

## ✨ Features

- **👀 Real-time Eye Tracking**: Moves the mouse cursor based on your gaze direction.
- **😉 Blink to Click**: Perform mouse clicks by blinking your left eye.
- **🚀 High Performance**: Uses MediaPipe's optimized Face Mesh for low-latency tracking.
- **🛑 Safety Failsafe**: Includes corner failsafe and keyboard interrupt ('q') for easy exit.
- **🖥️ Cross-Platform**: Works on Windows, macOS, and Linux (wherever Python & OpenCV run).

## 🛠️ Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/vvvvvivekkk/eye_controlled_mouse.git
    cd eye_controlled_mouse
    ```

2.  **Install dependencies:**
    It is recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

1.  **Run the application:**
    ```bash
    python main.py
    ```

2.  **Controls:**
    - **Move Cursor**: Move your head/eyes to look at different parts of the screen.
    - **Left Click**: Blink your **left eye** quickly.
    - **Quit**: Press `q` on your keyboard while the camera window is active.

## 📦 Dependencies

- `opencv-python`: For video capture and image processing.
- `mediapipe`: For facial landmark detection.
- `pyautogui`: For controlling the mouse programmatically.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
