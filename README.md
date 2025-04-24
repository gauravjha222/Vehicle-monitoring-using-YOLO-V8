# 🚗 Live Vehicle Monitoring using YOLOv8

This project presents a real-time **vehicle monitoring system** using **YOLOv8** by **Ultralytics**, wrapped in a user-friendly **Streamlit web app**. It enables detection and segmentation of vehicles and other objects from various sources including images, videos, webcam, RTSP streams, and YouTube videos.

---

##  Tech Stack

- **[YOLOv8](https://github.com/ultralytics/ultralytics)** – state-of-the-art object detection and segmentation.
- **Streamlit** – for building the interactive web interface.
- **OpenCV & PIL** – video/image handling and processing.
- **PyTube** – to handle YouTube video input.
- **NumPy** – for array and image data handling.

---

## Features

- **Supports Multiple Input Sources**:
  - Uploaded **images**
  - Local **videos**
  - **Webcam** feed
  - **RTSP** IP camera streams
  - **YouTube** videos

-  **Model Modes**:
  - Object **Detection**
  - Object **Segmentation**

-  **Interactive Controls**:
  - Confidence threshold slider
  - Toggle object tracking (ByteTrack / BoTSORT)
  - View raw detection outputs

---

** requirements 
ultralytics
streamlit
opencv-python
numpy
pillow
pytube

** To run
streamlit run app.py
