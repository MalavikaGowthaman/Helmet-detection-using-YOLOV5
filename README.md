# Helmet Detection Using YOLOv5

This project implements a motorcycle helmet detection system using the YOLOv5 object detection model. The system identifies whether riders are wearing helmets, which is crucial for enhancing safety and compliance.

Installation and Setup
1. Create a Conda Environment
Create a new Conda environment to manage dependencies:

```bash
conda create -n helmet_detection python=3.9
conda activate helmet_detection
```

2. Install PyTorch and YOLOv5
Install the required versions of PyTorch. Use the following command for CPU support:

```bash

pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/test/cpu
```

3. Clone the YOLOv5 Repository
Clone the YOLOv5 repository from GitHub:

``` bash

git clone https://github.com/ultralytics/yolov5
cd yolov5
```

4. Install YOLOv5 Requirements
Install the required dependencies for YOLOv5:

```
pip install -r requirements.txt

```
### Running the Model

## Load the YOLOv5 model: Use a pre-trained YOLOv5 model for helmet detection.

Test with images/videos: Detect helmet usage from images, videos, or live camera feeds.

## Features
- Real-time helmet detection via webcam
  
- Detects helmet usage from images and video files
  
Contact
For any questions or collaborations, feel free to reach out!
