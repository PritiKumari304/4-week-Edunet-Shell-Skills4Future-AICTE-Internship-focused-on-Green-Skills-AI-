# 🚦 Smart Street Scene Analyzer

A real-time computer vision system that analyzes street scenes to detect traffic light colors, monitor pedestrian and vehicle movement, and provide contextual understanding of urban environments.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-green)
![YOLO](https://img.shields.io/badge/YOLOv8-Object%20Detection-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🎯 Features

- **🚦 Traffic Light Color Detection**: Real-time identification of red, green, and yellow traffic lights
- **🚶 Pedestrian Movement Analysis**: Detect whether people are moving or stationary
- **🚗 Vehicle Motion Tracking**: Monitor movement patterns of cars, trucks, buses, and motorcycles
- **🎯 Object Persistence**: Maintain object IDs across frames using advanced tracking
- **📊 Real-time Analytics**: Live statistics and movement patterns
- **🎨 Visual Feedback**: Color-coded bounding boxes and status indicators

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- Webcam or video file
- 4GB+ RAM

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/PritiKumari304/4-week-Edunet-Shell-Skills4Future-AICTE-Internship-focused-on-Green-Skills-AI-.git
   cd 4-week-Edunet-Shell-Skills4Future-AICTE-Internship-focused-on-Green-Skills-AI-

# Detection Examples
Moving Vehicle: 🟢 Green bounding box with "car - moving" label
Stopped Pedestrian: 🔴 Red bounding box with "person - stopped" label
Traffic Light: Color-coded circle indicating current state (red/green/yellow)
