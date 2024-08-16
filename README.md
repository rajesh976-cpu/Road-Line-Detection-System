#Road Lane Detection System

Overview:-

The Road Lane Detection System is a Python-based project designed to identify and highlight lanes on the road in real-time video or static images. This project uses computer vision techniques and image processing to detect lanes and can be used in autonomous driving systems or driver assistance applications.

Features:-

Real-time Lane Detection: Detects lanes in video streams or webcam feed.

Image Processing: Applies filters and transformations to identify lane lines.

Hough Line Transform: Utilizes Hough Line Transform for line detection.

Region of Interest (ROI): Focuses on relevant areas in the image for better detection.

Customization: Adjustable parameters for fine-tuning lane detection.

Project Structure:-

plaintext:-

├── input_videos/          # Folder containing input video files
├── output_videos/         # Folder to save output videos with detected lanes
├── images/                # Folder containing test images
├── output_images/         # Folder to save output images with detected lanes
├── src/                   # Source code folder
│   ├── lane_detection.py  # Main script for lane detection
│   ├── utils.py           # Utility functions for image processing
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

Installation

Clone the repository:

bash

git clone https://github.com/username/road-lane-detection.git
cd road-lane-detection
Create and activate a virtual environment (optional but recommended):

bash

python3 -m venv venv
source venv/bin/activate
Install the required dependencies:

bash

pip install -r requirements.txt
Usage
Lane Detection in Video:

bash

python src/lane_detection.py --video input_videos/sample_video.mp4 --output output_videos/output_video.mp4
Lane Detection in Images:

bash

python src/lane_detection.py --image images/sample_image.jpg --output output_images/output_image.jpg
Lane Detection from Webcam:

bash

python src/lane_detection.py --webcam
Dependencies
Python 3.x
OpenCV
NumPy
Matplotlib
Install them using:

bash

pip install opencv-python numpy matplotlib
Customization
You can adjust the parameters for Canny edge detection, ROI, and Hough Transform in the lane_detection.py file to improve detection accuracy for different road conditions.

Examples
Lane Detection in Video

Lane Detection in Image
