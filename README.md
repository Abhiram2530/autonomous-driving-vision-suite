# autonomous-driving-vision-suite
This project aims to develop an integrated vision-based autonomous driving system using state-of-the-art models for real-time segmentation, object detection, object tracking, and lane detection. The system combines various models to detect and track objects, segment road elements, and identify lanes to make informed driving decisions.

## Features
- **Object Detection**: Utilizes YOLO or Faster R-CNN to detect vehicles, pedestrians, and other objects on the road.
- **Road Element Segmentation**: Employs the Segment Anything Model (SAM) for real-time segmentation of road elements such as traffic signs and road markings.
- **Lane Detection**: Implements LaneNet to accurately detect and segment lane boundaries.
- **Object Tracking**: Uses DeepSORT to track detected objects over time, maintaining object identities.
- **Decision Making**: Integrates the outputs from all models to make real-time driving decisions.

## Datasets
- **KITTI Vision Benchmark Suite**

## Installation
```bash
git clone https://github.com/yourusername/autonomous-driving-vision-suite.git
cd autonomous-driving-vision-suite
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt
