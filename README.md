EyeMouse Controller 🕹️👀
Welcome to EyeMouse, an innovative project that lets you control your computer's cursor using the power of your eyes! With eye-tracking technology, you can move the cursor across the screen and even trigger clicks with a blink. Powered by Python, MediaPipe, OpenCV, and PyAutoGUI, EyeMouse brings a futuristic, hands-free experience to your desktop.
🚀 Features

Eye-Controlled Cursor: Move your computer's cursor by simply looking at the screen.
Blink to Click: Perform a mouse click with a quick blink—intuitive and seamless.
Real-Time Tracking: Leverages MediaPipe's advanced face mesh for precise eye detection.
Lightweight & Easy to Use: Runs smoothly with minimal setup.
Open Source: Freely modify and enhance the project to suit your needs.

🎥 Demo
Control your cursor with a glance and click with a blink! (Insert a short demo video or GIF here to showcase EyeMouse in action.)
🛠️ Prerequisites
To get started, ensure you have the following installed:

Python 3.8+
Libraries:
opencv-python - For image processing and webcam capture.
mediapipe - For real-time eye tracking.
pyautogui - For controlling the mouse cursor.



📦 Installation

Clone the Repository:
git clone https://github.com/yourusername/EyeMouse.git
cd EyeMouse


Set Up a Virtual Environment (recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install Dependencies:
pip install opencv-python mediapipe pyautogui


Run the Application:
python eyemouse.py



🎮 How to Use

Launch the script (python eyemouse.py).
Allow access to your webcam.
Look at your screen to move the cursor—your eye movements will control its position.
Blink to trigger a left-click action.
Press q to quit the application.

Tip: Ensure good lighting and position your face clearly in front of the webcam for optimal performance.
🧑‍💻 How It Works
EyeMouse uses:

MediaPipe Face Mesh: Detects facial landmarks, focusing on eye positions for precise tracking.
OpenCV: Captures webcam input and processes video frames in real-time.
PyAutoGUI: Translates eye movements into cursor movements and blink detection into click events.

The system maps your eye movements to screen coordinates, smoothing the cursor's motion for a natural feel. A blink detection algorithm identifies intentional blinks to trigger clicks.
🔧 Troubleshooting

Cursor movement is jittery: Adjust your lighting or increase the smoothing factor in the code.
Blink detection is inconsistent: Ensure your face is well-lit and within the webcam's view.
Dependencies fail to install: Verify your Python version (3.8+) and try updating pip (pip install --upgrade pip).

🌟 Contributing
We'd love for you to contribute to EyeMouse! Here's how:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

Feel free to suggest new features like double-blink for right-click or gaze-based scrolling!
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
🙌 Acknowledgments

MediaPipe for amazing face mesh technology.
OpenCV for robust computer vision tools.
PyAutoGUI for seamless mouse control.


⭐ Star this repo if you find EyeMouse exciting!Have questions or ideas? Open an issue or reach out. Let's make hands-free computing even better! 👁️✨
