# Enhanced Vehicle Number Plate Recognition and Vehicle Analysis System

## Project Overview

This project is an AI-based Vehicle Number Plate Recognition and Vehicle Analysis System developed using YOLOv8, EasyOCR, OpenCV, and Python.

The system can automatically detect multiple vehicles in images and videos, identify vehicle types, determine vehicle colors, detect number plates, and extract plate text using Optical Character Recognition (OCR).

This project is an enhanced version of Project 1, which was limited to basic number plate detection. Project 2 introduces multiple vehicle detection, vehicle classification, color recognition, image processing, and video processing capabilities.

---

## Features

### Vehicle Detection

Detects multiple vehicles in a single image or video frame using YOLOv8.

Supported vehicle categories:

* Car
* Motorcycle
* Bus
* Truck

### Vehicle Type Classification

Automatically classifies each detected vehicle according to its category.

### Vehicle Color Detection

Determines the dominant color of each vehicle.

Supported colors:

* Black
* White
* Gray
* Silver
* Red
* Blue
* Green
* Yellow
* Orange
* Brown

### Number Plate Detection

Uses a custom YOLOv8 model to detect vehicle number plates.

### OCR Text Recognition

Uses EasyOCR to extract alphanumeric text from detected number plates.

### Image Processing

Processes uploaded images and generates annotated output images.

### Video Processing

Processes uploaded videos frame-by-frame and generates annotated output videos.

### Output Annotation

Displays:

* Vehicle Type
* Vehicle Color
* Number Plate Text

Example:

Car | White | LEA-1234

Truck | Blue | ICT-5678

---

## Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* EasyOCR
* NumPy
* Matplotlib
* Google Colab

---

## Navigation Flow

Upload Image / Video

↓

Vehicle Detection (YOLOv8)

↓

Vehicle Type Classification

↓

Vehicle Color Detection

↓

Number Plate Detection

↓

OCR Text Recognition

↓

Result Annotation

↓

Output Image / Video Generation

---

## Project Structure

```text
Project Folder
│
├── best.pt
├── vehicle_analysis.ipynb
├── README.md
├── sample_images/
├── sample_videos/
├── output/
│   ├── annotated_image.jpg
│   └── annotated_video.mp4
```

---

## How to Run

1. Open the notebook in Google Colab.
2. Install required dependencies.
3. Upload the custom number plate model (best.pt).
4. Run all notebook cells.
5. Upload an image or video.
6. View the generated output.
7. Download the annotated image or video.

---

## Project Improvements from Project 1

### Project 1

* Basic Number Plate Detection
* OCR Text Extraction
* Single Feature System

### Project 2

* Multiple Vehicle Detection
* Vehicle Type Classification
* Vehicle Color Detection
* Number Plate Detection
* OCR Text Extraction
* Image Processing
* Video Processing
* Annotated Output Generation

---

## Future Enhancements

* Real-time webcam detection
* Vehicle tracking
* Parking management integration
* Cloud deployment
* Advanced OCR accuracy improvement

University: _____________________
