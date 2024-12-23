# Virtual Mouse

This repository provides a Python-based implementation for controlling a computer's mouse actions using hand gestures, leveraging OpenCV, MediaPipe, and PyAutoGUI. The application detects specific hand gestures through a webcam and maps them to corresponding mouse actions like moving the cursor, left-clicking, right-clicking, double-clicking, or even taking screenshots.

## Features

- **Mouse Movement**: Control the mouse pointer by moving your index finger in the camera's field of view.
- **Left Click**: Perform a left-click gesture to simulate a left mouse button click.
- **Right Click**: Perform a right-click gesture to simulate a right mouse button click.
- **Double Click**: Trigger a double-click using a specific hand gesture.
- **Screenshot**: Capture the screen instantly with a unique hand gesture.
- **Real-time Processing**: All gestures are detected in real-time, ensuring smooth interaction.

## Installation

### Prerequisites

Make sure you have the following installed:
- Python 3.7+
- Webcam for video input

### Install Dependencies

Install the required libraries using pip:
```bash
pip install opencv-python mediapipe pyautogui pynput numpy
```

### Usage

Clone this repository:
```bash
git clone https://github.com/Sraghav97/virtual-mouse.git
cd virtual-mouse
```

Run the application:
```bash
python main.py
```

Use the following gestures to perform actions:
- **Mouse Movement**: Move your index finger to control the cursor.
- **Left Click**: Make a gesture with the index finger and thumb positioned close, and the other fingers extended.
- **Right Click**: A gesture with specific alignment of fingers as detected by the system logic.
- **Double Click**: A combined gesture detected by the system logic.
- **Screenshot**: Close your thumb and index finger while keeping other fingers extended.

Press 'q' to exit the application.

## File Descriptions

- **main.py**: The main entry point for the application. It initializes the webcam feed, detects hand landmarks, and maps gestures to mouse actions.
- **utils.py**: A helper module providing utility functions:
  - `get_angle()`: Calculates the angle between three points.
  - `get_distance()`: Computes the normalized distance between two points.
- **gestures.ipynb**: A Jupyter Notebook file (if applicable) to experiment with and visualize gesture detection concepts.

## How It Works

- **Hand Detection**: Uses MediaPipe's Hands module to detect hand landmarks in the webcam feed.
- **Gesture Analysis**: Processes the positions and angles of hand landmarks to identify specific gestures.
- **Action Mapping**: Maps recognized gestures to mouse actions (move, click, double-click, or screenshot).
- **Real-time Feedback**: Displays the video feed with visual indicators for detected gestures and actions performed.
