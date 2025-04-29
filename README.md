# AI-Virtual-Mouse
This project uses computer vision and machine learning techniques to control the mouse pointer with hand gestures. The system uses Mediapipe for hand tracking and OpenCV for image processing to detect hand gestures in real-time. The goal of the project is to provide an accessible way for users to control their computer using just hand movements, making it useful for people with disabilities or those looking for an alternative input method.
Key Features:
Hand Gesture Recognition: Detects hand gestures using Mediapipe.
Mouse Control: Translate hand movements into mouse pointer movements.
Click Simulation: Allows for left and right-click operations.
Real-time Processing: The system runs in real-time using the webcam.
Technologies Used:
Python: Programming language used for the project.
OpenCV: For image processing and computer vision tasks.
Mediapipe: For hand tracking.
Pyautogui: For controlling the mouse.
Autopy: For automating keyboard/mouse control (if used).
Installation:
To run this project, you need to have Python installed on your system. You also need the following libraries:
OpenCV
Mediapipe
Pyautogui
Autopy
Use the following command to install the dependencies:
pip install opencv-python mediapipe pyautogui autopy
Usage:
Clone the repository:
https://github.com/SujathaMummana/AI-Virtual-Mouse.git
Run the project:
python aivirtualmouseproject.py
The webcam will open, and the program will track your hand movements to control the mouse cursor.
