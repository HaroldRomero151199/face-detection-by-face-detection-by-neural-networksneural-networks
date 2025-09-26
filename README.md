# Project: Face, Hand, and Pose Detection with Neural Networks

This project enables real-time detection of faces, hands, and human poses using neural network models and your webcam. It includes examples for face detection with Haar Cascades and CNN, hand detection with YOLOv8, and human pose detection with YOLOv8 Pose.

## Features
- Real-time video capture from webcam.
- Face detection using Haar Cascades and CNN models.
- Hand detection using YOLOv8.
- Human pose detection using YOLOv8 Pose.
- Example scripts for video processing and result visualization.

## Installation
1. **Clone the repository**
   ```powershell
   git clone <repository-URL>
   cd <repository-name>
   ```
2. **Install Python 3.8 or higher**

3. **Install required dependencies**
   ```powershell
   pip install opencv-python ultralytics numpy
   ```
   If you use Jupyter Notebook, also install:
   ```powershell
   pip install notebook
   ```

4. **Download pre-trained models**
   - `hand_yolov8n.pt` and `yolov8n-pose.pt` (already included in the project folder)
   - `deploy.prototxt.txt` and `res10_300x300_ssd_iter_140000.caffemodel` for face detection (already included)

## Usage
- Open and run the notebooks (`intro_camara.ipynb`) to test the detection examples.
- Press 'q' in the video window to exit the capture.

## Requirements
- Windows 10/11
- Python 3.8+
- Webcam

## Credits
- YOLOv8 models by [Ultralytics](https://ultralytics.com/)
- OpenCV for image processing

## License
This project is for academic and educational use.