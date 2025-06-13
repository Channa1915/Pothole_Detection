# 🕳️ Pothole Detection System using YOLOv8

This project is an AI-powered web application for detecting potholes in **images and videos** using the **YOLOv8 deep learning model**. It is designed for road safety monitoring and infrastructure maintenance.

## 📌 Project Overview

Potholes are a common cause of road accidents and vehicle damage. Traditional manual inspection methods are time-consuming and inefficient. This system leverages **computer vision and deep learning** to automate pothole detection with high accuracy and speed.

### 🔍 Features

- 📸 **Image Segmentation**: Upload an image and detect potholes with bounding boxes and segmentation masks.
- 🎥 **Video Segmentation**: Upload a video to detect potholes frame-by-frame.
- ⚙️ **Real-time Output**: Immediate visualization of results after detection.
- ⬇️ **Download Option**: Save the processed image or video for reporting and analysis.
- 🌐 **Web Interface**: Built using Streamlit for easy interaction.

---

## 🚀 Technologies Used

- **Python** 🐍
- **YOLOv8** (via Ultralytics)
- **OpenCV** – for video frame handling and visualization
- **Streamlit** – web app interface
- **NumPy, Pandas** – for numerical and data operations
- **Roboflow** – dataset preparation and model training

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/pothole-detection-system.git
cd pothole-detection-system
pip install -r requirements.txt
