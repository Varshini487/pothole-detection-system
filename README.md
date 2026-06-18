# 🚗 Pothole Detection System

A **computer vision system** that detects road potholes from dashcam video using YOLO object detection. Real-time processing (<50ms per frame) suitable for fleet management and municipal road maintenance.

## 🎯 Use Cases
- Fleet vehicle dashcams → automatic pothole reporting
- Municipal road inspection automation
- Insurance claim validation
- Route safety monitoring

## 🛠️ Tech Stack
- **YOLOv8** – real-time object detection
- **OpenCV** – video processing
- **PyTorch** – deep learning backend
- **Streamlit** – demo interface
- **FastAPI** – production API

## 📊 Performance
- Inference: 35ms per frame (GPU), 150ms (CPU)
- Recall: 92% (catches most potholes)
- Precision: 87% (few false positives)
- FPS: 28 (GPU), 6 (CPU)

## 🚀 Quick Start
```bash
git clone https://github.com/Varshini487/pothole-detection-system
cd pothole-detection-system
pip install -r requirements.txt
streamlit run app.py
```
