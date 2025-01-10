# Helmet Detection

This repository contains a **Helmet Detection System** implemented using the YOLOv8 object detection model. The system is capable of detecting helmets with high speed and accuracy from both live video streams and static image inputs.

---

## Features

- 🛡️ **Helmet Detection**: Accurately detects helmets in live video streams and image files.
- ⚡ **High Speed & Efficiency**: Optimized using the YOLOv8 model for real-time performance.
- 📊 **Custom Dataset**: Utilized annotated datasets for improved detection accuracy.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AaftabShaikh77/Helmet-Detection.git
   cd Helmet-Detection
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the pre-trained YOLOv8 weights:
   - Visit the [YOLOv8 repository](https://github.com/ultralytics/ultralytics) for model weights.
   - Save the weights file in the project directory.

---

## Usage

### Detecting Helmets in Images

1. Place your test images in the `images/` directory.
2. Run the following command to detect helmets:
   ```bash
   python detect.py --source images/ --weights yolov8-weights.pt
   ```

### Detecting Helmets in Live Video

1. Connect your camera or use a video file.
2. Execute the following command:
   ```bash
   python detect.py --source 0 --weights yolov8-weights.pt
   ```
   Replace `0` with the path to your video file if needed.

---

## Dataset

The dataset used for training was annotated to include:
- Images of people with helmets.
- Images of people without helmets.

The annotations were formatted in YOLO format for seamless integration with YOLOv8.

---

## Results

- Achieved **high accuracy** in detecting helmets from both static images and live video streams.
- Demonstrated **real-time performance** for video inputs.

---

## Requirements

- Python 3.8 or higher
- Ultralytics YOLOv8
- OpenCV
- Torch


---

## Repository Link

Find the code and implementation details on GitHub: [Helmet Detection](https://github.com/AaftabShaikh77/Helmet-Detection)


---

## Acknowledgments

Special thanks to the creators of YOLOv8 and the open-source community for their support and resources.
