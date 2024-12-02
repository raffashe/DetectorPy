# Detector-Py

**Detector-Py** is a real-time object detection project using the YOLOv8 model and the `ultralytics` library. The project captures real-time images from the webcam and detects objects present in the scene, displaying the result in a video window.

![imagem detectorpy](https://github.com/user-attachments/assets/f9085e2a-a6f6-405a-8ae4-a3ae0eaa5786)

## Technologies Used

- **Python 3.9.13**
- **YOLOv8** (You Only Look Once, version 8)
- **Ultralytics**

## Prerequisites

Before running the project, you need to install the dependencies. It is recommended to use a virtual environment (such as `venv` or `virtualenv`).

### 1. Clone this repository:
```bash
git clone https://github.com/yourusername/detector-Py.git
```

### 2. Create and activate a virtual environment (optional, but recommended):
```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
.\venv\Scripts\activate   # For Windows
```

### 3. Install the project dependencies:
```bash
pip install ultralytics
```

## How to Run the Project

After installing the dependencies, you can run the code to start object detection:

```bash
python main.py
```

The script will open the webcam and start detecting objects in real-time, showing the results on the screen.

## Project Features

- **Real-Time Object Detection:** The project uses YOLOv8 to detect various objects in the scene captured by the webcam.
- **Immediate Visualization:** The object detection results are displayed directly on the screen, highlighting the identified objects with bounding boxes.

## Future Expansions

> You can use this code as a foundation to expand your idea, whether to implement features like object tracking, detection in recorded videos, integration with other computer vision tools, or any other project related to real-time object detection.
