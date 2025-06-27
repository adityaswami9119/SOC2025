# SOC2025
# 🚗 Custom Object Detection using YOLOv5

This project implements a custom object detection pipeline using YOLOv5 to detect vehicles. The dataset is obtained from Roboflow's Vehicles-OpenImages and trained using PyTorch and OpenCV.

## 📂 Contents
- Download and preprocessing of the dataset
- YOLOv5 setup and configuration
- Model training and validation
- Inference on test images
- Result visualization

## 🧠 Model
The model used is **YOLOv5** (You Only Look Once, version 5), which is known for its speed and accuracy in real-time object detection tasks.

## 📊 Dataset
Dataset: [Vehicles - OpenImages](https://public.roboflow.com/object-detection/vehicles-openimages)  
Provided by [Roboflow](https://roboflow.com)

The dataset includes:
- Images of various vehicle types
- Bounding box annotations in YOLO format

## ⚙️ Requirements
Install the following Python packages before running the notebook:

```bash
pip install matplotlib opencv-python numpy

git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
