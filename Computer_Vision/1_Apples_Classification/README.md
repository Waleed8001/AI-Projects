# 🍎 Apple Quality Detection – YOLOv8m

A computer vision system built using Ultralytics YOLOv8n to classify apples into four quality categories:
- Red Apple
- Green Apple
- Used Apple
- Rotten Apple

### 🚀 Project Overview

This project aims to automate fruit quality inspection using a lightweight YOLOv8 model. The system can run efficiently even on low-resource devices while maintaining strong detection accuracy.

The model is trained on a custom dataset and deployed with a Streamlit web interface for easy testing.

### 🧠 Features
- Custom object detection model using YOLOv8n
- Detects 4 apple categories in images or video
- Real-time inference using webcam
- Clean and interactive Streamlit UI
- Compatible with CPU and small GPUs (2GB+)

### 📸 Demo

(Add your Streamlit link or screenshots here)

🛠️ Technologies Used
- Python
- Ultralytics YOLOv8
- OpenCV
- Streamlit

### ▶️ Run the Project
1. Install packages
```bash
pip install ultralytics streamlit opencv-python
```

3. Run Streamlit app
```bash
streamlit run app.py
```

### 🤖 Training the Model
```bash
yolo train model=yolov8n.pt data=data.yaml epochs=100 imgsz=640
```

### ⭐ Contribute

Pull requests and suggestions are welcome!

### 📬 Contact

For queries or collaboration:
Muhammad Waleed Kamal – [www.linkedin.com/in/muhammad-waleed-kamal-3910422b3](LinkedIn Link)
