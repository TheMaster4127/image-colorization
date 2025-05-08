# 🖼️ Black and White to Color: An Image Colorization Approach

This project uses a deep learning model to automatically colorize grayscale images. It leverages a pre-trained neural network built with the Caffe framework and processes images using Python and OpenCV.

## 🚀 Features
- Fully automated black-and-white to color conversion
- Based on a pre-trained deep neural network
- Converts grayscale images using LAB color space processing
- Works with any standard image input (JPG, PNG, etc.)

## 🧰 Requirements
- Python 3.x
- OpenCV
- NumPy
- argparse
- Pre-trained model files:
  - `colorization_deploy_v2.prototxt`
  - `colorization_release_v2.caffemodel`
  - `pts_in_hull.npy`

Install dependencies:
```bash
pip install opencv-python numpy argparse
