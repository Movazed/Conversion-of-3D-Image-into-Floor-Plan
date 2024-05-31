# Conversion-of-3D-Image-into-Floor-Plan

# 3D to Floor Plan Converter

This project provides a Python script to convert a top-down 3D image into a 2D floor plan using OpenCV. The script processes the image to detect edges, find contours, and draw the floor plan.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

You can install the required libraries using pip:

```sh
pip install opencv-python numpy matplotlib

git clone https://github.com/your-username/3d-to-floor-plan.git
cd 3d-to-floor-plan

image_path = 'D:\\Projects\\workspace\\3d to plain using CV\\samples\\img_1.jpg'

The script will generate and save the following images in the same directory as the input image:

Original image
Preprocessed image (blurred)
Edge-detected image
Final floor plan
