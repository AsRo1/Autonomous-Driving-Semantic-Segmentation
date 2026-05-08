# -Autonomous-Driving-Semantic-Segmentation


##  Project Overview
This repository contains the implementation of a soft computing/deep learning project focused on **Semantic Segmentation for Autonomous Vehicles**. The primary objective is to accurately classify pixel-level details in road scenes (e.g., vehicles, pedestrians, roads, and obstacles) to assist in self-driving perception systems.

This project utilizes the [Lyft Udacity Challenge Dataset](https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge), a large-scale collection of RGB camera images and their corresponding segmented masks.

##  Dataset Details
The model is trained and evaluated using the **Lyft Udacity Challenge Dataset**.
* **Input:** RGB Camera Images (`CameraRGB/`)
* **Ground Truth:** Semantic Segmentation Masks (`CameraSeg/`)
* **Size:** ~5 GB
* **Source:** Kaggle (`kumaresanmanickavelu/lyft-udacity-challenge`)

## 🚀 Setup & Installation

### Prerequisites
Ensure you have the following dependencies installed. It is recommended to use Python 3.8+ and a virtual environment.

```bash
pip install numpy pandas matplotlib
pip install torch torchvision torchaudio   # If using PyTorch
# OR
pip install tensorflow keras               # If using TensorFlow/Keras
