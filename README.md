



# Vision-Based Navigation System for Self-Driving Car

The **Vision-Based Navigation System for Self-Driving Car** is an AI-powered autonomous driving project that uses **Computer Vision**, **Deep Learning**, and **Real-Time Inference** techniques to understand road environments and support intelligent vehicle navigation.

The system can:
* Detect road lanes
* Identify surrounding objects
* Predict steering angles
* Support autonomous navigation in real time

# Key Features
* Real-time Lane Detection
* Object Detection
* Steering Angle Prediction
* Real-Time Inference Pipeline
* AI-based Navigation Assistance

# How AI is Used in This Project
Artificial Intelligence is the core part of this navigation system. AI helps the vehicle understand road environments and make intelligent driving predictions automatically.

## AI Functionalities

### 🔹 Computer Vision
* Lane detection
* Road understanding
* Object recognition
* Video frame analysis

### 🔹 Deep Learning
* Steering angle prediction
* Learning driving behavior
* Feature extraction from images

### 🔹 YOLOv11
* Lane segmentation
* Object detection
* Real-time environment analysis

### 🔹 CNN Regression Model
* Steering prediction
* Navigation assistance

# Research Paper Implementation
This project implements and extends the following research work:

*End to End Learning for Self-Driving Cars*
Research Paper -https://arxiv.org/abs/1604.07316

The original paper proposes a CNN architecture that maps raw image pixels directly to steering commands.
This implementation follows the same end-to-end learning paradigm and extends it using:
* YOLO-based lane segmentation
* Real-time perception pipeline
* Modern computer vision techniques

#  Dataset
The project uses a driving dataset containing:
* Front camera images
* Steering angle labels
* Road scenes under varying lighting and traffic conditions

###  Dataset Details
* Approximately **45,500 images**
* Dataset size: **2.2 GB**
* Recorded around **Rancho Palos Verdes** and **San Pedro, California**
* One of the original self-driving datasets created in **2017**

###  Data Format
```text id="h2tw03"
filename.jpg steering_angle
```

###  Dataset Source

🔗 [Download Dataset](https://drive.google.com/file/d/1Ue4XohCOV5YXy57S_5tDfCVqzLr101M7/view?utm_source=chatgpt.com)


# Technologies Used
* Python
* TensorFlow
* OpenCV
* YOLOv11
* NumPy
* Pandas
* Matplotlib

# Project Structure

VISION-BASED-NAVIGATION-SYSTEM
│
├── data/
│   ├── driving_dataset/
│   └── steering_wheel_image.jpg
│
├── model_training/
│   ├── train_lane_detection/
│   │   ├── runs/
│   │   ├── training_lane_detection.ipynb
│   │   ├── yolo11n-seg.pt
│   │   └── yolo11m-seg.pt
│   │
│   └── train_steering_angle/
│       ├── logs/
│       ├── save/
│       ├── driving_data.py
│       ├── model.py
│       └── train.py
│
├── saved_models/
│   ├── lane_segmentation_model/
│   ├── object_detection_model/
│   │   └── yolo11s-seg.pt
│   └── regression_model/
│
├── src/
│   ├── inference/
│   │   ├── run_fsd_inference.py
│   │   └── run_steering_angle_prediction.py
│   │
│   ├── models/
│   │   ├── __init__.py
│   │   └── model.py
│   │
│   ├── utils/
│   └── tests/
│
├── notebooks/
├── requirements.txt
├── README.md
└── setup.py

#  Project Demo Video
Demonstration video included showing:
* Lane detection
* Object detection
* Steering prediction
* Real-time navigation assistance
* https://github.com/user-attachments/assets/5b356924-832c-45d5-abcb-ebc47d490cf9



# Future Improvements
* Traffic Sign Detection
* Autonomous Braking
* LiDAR Integration
* Reinforcement Learning
* Full Autonomous Navigation



# Project Goal
The goal of this project is to develop an intelligent AI-based navigation system capable of understanding road scenes, detecting lanes and obstacles, and predicting steering directions for autonomous driving support.



# Author

Developed by Vijay Prajapati, M.Sc. M.Tech in Data Science, Student at IIT Jodhpur interested in:
* Artificial Intelligence
* Deep Learning
* Computer Vision
* Autonomous Systems
