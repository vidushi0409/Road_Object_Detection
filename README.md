# Foggy_YOLOv10

## Road Object Detection in Foggy Complex Scenes using Improved YOLOv10

A deep learning-based road object detection system designed to accurately detect road objects in foggy and low-visibility environments using an improved YOLOv10 model. The project also includes a Flask web application that allows users to upload road images and visualize real-time object detection results.

## Features

- Road object detection using an improved YOLOv10 model
- Detection in foggy and low-visibility conditions
- Flask-based web interface
- Upload and detect objects in custom images
- Bounding box visualization with confidence scores
- Export trained model to ONNX format
- Real-time inference

## Object Classes

The model is trained to detect the following classes:

- Bus
- Car
- MotorBike
- Bicycle
- Person

## Technologies Used

- Python
- YOLOv10 (Ultralytics)
- PyTorch
- Flask
- OpenCV
- NumPy
- HTML
- CSS
- JavaScript

## Project Structure

Foggy-YOLOv10/
├── results/
├── static/
├── templates/
├── test_data/
├── uploads/
└── README.md
├── README.roboflow
├── app.py
├── best.pt
├── data.yaml
├── requirements.txt


## Model Training

The model was trained using the Ultralytics YOLOv10 framework on a custom foggy road object detection dataset.

Training configuration:

- Image Size: 640 × 640
- Epochs: 60
- Batch Size: 16
- Classes: 5

## Results

The trained model can successfully detect:

- Cars
- Buses
- Motorcycles
- Bicycles
- Pedestrians

even under foggy and low-visibility conditions.

## Dataset

The dataset contains annotated foggy road images used for training and validation.

Dataset configuration is available in:

```
data.yaml
```

---

## Future Improvements

- Video object detection
- Night-time detection
- Rain and snow detection
- Model optimization for edge devices
- Improved detection accuracy using larger datasets

---


