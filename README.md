# virtual_mouse_using_hand_gesture
This project implements a Virtual Mouse that allows you to control your computer cursor using hand gestures captured via a webcam.
It uses MediaPipe for hand tracking, OpenCV for video processing, and PyAutoGUI for controlling the mouse cursor and clicks.

🚀 Features

 🖐️ Tracks a single hand using MediaPipe

 🖱️ Controls the mouse pointer using the index fingertip

 👆 Smooth pointer movement using interpolation

 🤏 Pinch gesture (thumb + index) to perform a mouse click

 🔁 Real-time webcam feed with hand landmarks

 🎯 High accuracy and low latency


🛠️ Technologies Used

-> Python

-> OpenCV

-> MediaPipe

-> PyAutoGUI

-> NumPy

📦 Installation
1. Clone the repository
   
 -> git clone <https://github.com/hello-akhilesh/virtual_mouse_using_hand_gesture>

 -> cd <virtual_mouse_using_hand_gesture>

3. Install dependencies
   
pip install opencv-python mediapipe pyautogui numpy

🎮 Controls

Gesture	Action

1. Index finger moving	-> Move mouse cursor

2. Thumb + Index pinch	-> Left click

3. Press q to	Quit the application
