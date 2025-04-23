# SketchSpace: Air Canvas Whiteboard Application

SketchSpace is an innovative, AI-powered whiteboard application that allows users to draw in the air using real-time hand gesture recognition. By combining MediaPipe and OpenCV with Python, SketchSpace eliminates the need for touch or stylus input — enabling users to sketch, select tools, and interact using just their hands.

---

## 🧠 Features

- ✋ Real-time hand tracking using **MediaPipe**
- 🎨 Gesture-based air drawing on a virtual canvas
- 🖼️ Shape drawing: supports circles, rectangles, and more
- 📷 Works with any standard camera
- 🧩 Built using **OpenCV**, **NumPy**, and **Python**
- 👩‍🏫 Ideal for online teaching, creative design, and interactive demos
- 🌱 Paperless and eco-friendly alternative to traditional drawing

---

## 🔧 Technologies Used

| Component       | Description                              |
|----------------|------------------------------------------|
| Python          | Backend logic and application core       |
| MediaPipe       | Real-time hand gesture tracking          |
| OpenCV          | Image processing and computer vision     |
| NumPy           | Array processing and calculations        |

---

## 📋 Problem Statement

Smartphone overuse among children and the extensive use of paper for trivial tasks pose significant health and environmental issues. SketchSpace introduces a hands-free, screen-safe, and paperless way to promote creative and educational interactions through a simple camera-based setup.

---

## 🚀 Setup Instructions

### Requirements
- Python 3.x
- Webcam (built-in or external)

### Install Dependencies

```bash
pip install opencv-python mediapipe numpy
```

## Run the Application
```bash
python sketchspace.py
```
📈 System Workflow
Launch the app on a device with a camera.

Position your hand at a visible distance from the camera.

Perform gestures to select tools or start drawing.

Watch your air sketches come to life on the screen.

🔍 Evaluation Metrics
Accuracy across varied lighting and hand types

Low Latency for real-time interaction

Frame Drop Rate monitoring for performance tuning

Comparative Analysis with similar gesture-based systems

📚 Future Enhancements
🖐️ Multi-hand gesture support

🧠 Customizable gestures and shapes

🗣️ Voice command integration

🌐 AR/VR compatibility for immersive interaction

👥 Real-time collaboration and cloud sync
