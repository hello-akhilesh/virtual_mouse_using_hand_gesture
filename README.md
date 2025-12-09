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

📸 How It Works

1. MediaPipe detects hand landmarks

2. The index fingertip (landmark 8) is mapped to screen coordinates

3. Pointer movement is smoothed for natural control

4. If distance between thumb (landmark 4) and index fingertip is small → mouse click

5. Display window shows real-time camera feed with tracking

🛠️ Technologies Used

-Python

-OpenCV

-MediaPipe

-PyAutoGUI

-NumPy

📦 Installation
1. Clone the repository
   
-git clone <https://github.com/hello-akhilesh/virtual_mouse_using_hand_gesture>
-cd <virtual_mouse_using_hand_gesture>

3. Install dependencies
pip install opencv-python mediapipe pyautogui numpy

🎮 Controls
Gesture	Action

-Index finger moving	-> Move mouse cursor
-Thumb + Index pinch	-> Left click
-Press q	Quit the application
