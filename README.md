# Air-Canvas
**Air Canvas** is a fun and interactive computer vision project built with **Python** and **OpenCV** that lets you draw in the air using only your webcam and colored objects (Red, Green, Blue). It uses real-time object detection and tracking to simulate a virtual whiteboard.
# Built With:
- Python
- OpenCV
- NumPy
  
# Features
- Draw using **red**, **blue**, or **green** colored objects
- Eraser mode to remove parts of the drawing
- Adjustable **brush size** (1, 2, 3 keys)
- Save your drawing as an image file (press `S`)
- Clear the canvas anytime (press `C`)
- Real-time contour detection using webcam
# How it Works

- Detects colored markers using **HSV color filtering**
- Tracks the position of the marker’s contour
- Uses that position to draw lines on a virtual canvas
- Combines the canvas with the live webcam feed
  
# Controls
| Key        | Action                     |
|------------|-----------------------------|
| `1`        | Small Brush                 |
| `2`        | Medium Brush                |
| `3`        | Large Brush                 |
| `E`        | Toggle Eraser Mode          |
| `C`        | Clear Canvas                |
| `S`        | Save Drawing (`.png`)       |
| `Q`        | Quit the Application        |

# Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/air-canvas-opencv.git
   cd air-canvas-opencv
2. **Install dependencies manually**:
   ```bash
   pip install opencv-python numpy

3. **Run the Project**
   ```bash
   python air_can.py

# License
This project is licensed under the MIT License.
Feel free to fork, modify, and share it
