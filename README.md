#  AI Precision Spraying Drone using YOLOv8 and Raspberry Pi

##  Overview

The AI Precision Spraying Drone is an intelligent agriculture project designed to detect plant diseases using computer vision and perform targeted pesticide or fertilizer spraying. Instead of spraying the entire field, the system identifies infected plant regions and enables precise spraying only where required.

The project utilizes the YOLOv8 object detection model trained on a custom plant disease dataset obtained from Roboflow. The trained model is optimized for deployment on Raspberry Pi using the NCNN format, making it suitable for real-time edge AI applications in smart farming.

This solution helps reduce pesticide usage, minimize environmental impact, improve crop health, and increase agricultural efficiency.

---

#  Objectives

- Detect plant diseases in real time using Artificial Intelligence.
- Reduce excessive pesticide and fertilizer usage.
- Enable precision spraying for infected plants only.
- Deploy an optimized deep learning model on Raspberry Pi.
- Improve farming efficiency using computer vision and edge computing.

---

# Features

- Plant disease detection using YOLOv8
- Custom dataset integration using Roboflow
- Model training on Google Colab with GPU acceleration
- Automatic dataset download and preprocessing
- Export trained model to NCNN format
- Raspberry Pi deployment support
- Lightweight YOLOv8 Nano model for edge devices
- Real-time object detection capability
- Optimized for precision agriculture applications

---

#  Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| YOLOv8 | Object Detection |
| Ultralytics | YOLOv8 Framework |
| Roboflow | Dataset Management |
| Google Colab | Model Training |
| PyTorch | Deep Learning |
| OpenCV | Image Processing |
| Raspberry Pi 5 | Edge AI Deployment |
| NCNN | Model Optimization |
| NumPy | Numerical Computation |

---

#  Project Workflow

```
Plant Images
      │
      ▼
Roboflow Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
YOLOv8 Nano Training
      │
      ▼
Model Evaluation
      │
      ▼
Export to NCNN
      │
      ▼
Deploy on Raspberry Pi
      │
      ▼
Real-Time Disease Detection
      │
      ▼
Precision Spraying
```

---

# 🧠Model Training

The YOLOv8 Nano model was trained using Google Colab GPU to ensure faster convergence and efficient model performance.

Training includes:

- Dataset download using Roboflow
- Automatic preprocessing
- YOLOv8 model initialization
- Training over multiple epochs
- Validation after each epoch
- Saving best model weights
- Exporting the trained model for Raspberry Pi deployment

---

#  Disease Detection

The trained model is capable of identifying multiple plant diseases from leaf images.

The detection process includes:

- Image acquisition
- Object detection
- Disease classification
- Bounding box generation
- Confidence score prediction

The detected infected regions can then be used for targeted pesticide spraying.

---

#  Raspberry Pi Deployment

The trained model is exported into NCNN format, making it lightweight and suitable for Raspberry Pi deployment.

Advantages include:

- Faster inference
- Lower memory consumption
- Reduced computational requirements
- Real-time performance
- Edge AI compatibility

---

#  Model Performance

The trained model achieved high detection performance during validation.

| Metric | Value |
|---------|-------|
| Precision | 97.5% |
| Recall | 97.2% |
| mAP@50 | 98.8% |
| mAP@50-95 | 86.2% |

---

#  Repository Structure

```
AI-Precision-Spraying-Drone
│
├── Drone_Project.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Future Enhancements

- Live camera integration with Raspberry Pi
- Autonomous drone navigation
- GPS-assisted spraying
- Mobile application for monitoring
- Cloud dashboard for analytics
- Multiple crop support
- IoT sensor integration
- Real-time disease alerts

---

#  Learning Outcomes

Through this project, I gained practical experience in:

- Deep Learning
- Computer Vision
- Object Detection
- YOLOv8 Model Training
- Roboflow Dataset Management
- Google Colab GPU Training
- Raspberry Pi Deployment
- Edge AI Optimization
- Precision Agriculture Solutions

---

# License

This project is developed for educational and research purposes.
