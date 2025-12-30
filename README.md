# Vehicle_Detection
Vehicle detection using YOLOv8 on traffic camera and aerial road images.
# Road / Object Detection Using Deep Learning

This project focuses on detecting road vehicles (cars, motorcycles, trucks)
using deep learning-based object detection models (YOLOv8).

Two different models were trained and evaluated to analyse how the training image domain affects detection performance.

## Models
- **Aerial Model**: Trained on aerial / top-view road images
- **Traffic Camera Model**: Trained on traffic surveillance camera images

## Key Idea
Object detection models perform best when test images are visually
similar to the images used during training.
This project demonstrates domain dependency in object detection.

## Repository Structure
- `final_project.ipynb`: Main notebook for loading models and testing
- `models/`: Trained YOLOv8 models (`best.pt`)
- `test_images/`: Sample images used for testing
- `results/`: Detection outputs

## Technologies
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- PyTorch

