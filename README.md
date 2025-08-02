# Final Project

This repository contains a Google Colab notebook for the Abnormal Event Detection in Avenue dataset.

## 📓 Notebook
Final_Soc_Project_.ipynb


## 📌 Requirements

Common dependencies used:
- `cv2`
- `matplotlib`
- `numpy`
- `sklearn`
- `torch`

> ✅ Best run in Google Colab

## 🚀 How to Run

1. Open the notebook in Colab.
2. Run each cell sequentially.
3. (Optional) Upload your own data or modify parameters for experimentation.

## 📚 Project Description

**Anomaly video detection** is the process of identifying unusual or unexpected activities in video surveillance footage. 

### 🔍 How It Works:
1. **Object Detection** (e.g., YOLO):  
   Identifies objects like people, vehicles, or bags in each frame.

2. **Tracking** (e.g., DeepSORT):  
   Tracks these objects across frames to understand movement and behavior.

3. **Anomaly Detection**:  
   Flags any behavior that deviates significantly from normal patterns.

### 🧠 Techniques Used:
- **Pretrained YOLOv5** for real-time object detection  
- **DeepSORT** for multi-object tracking    
- **Custom training or thresholding** to define what counts as an "anomaly"

### ⚙️ Applications:
- Smart surveillance in malls, airports, and railway stations  
- Industrial safety monitoring  
- Traffic violation detection  
- Public safety enforcement
