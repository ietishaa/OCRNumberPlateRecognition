# OCRNumberPlateRecognition
# Number Plate Detection & OCR

This project uses a trained YOLOv8 model to detect vehicle number plates in videos and performs OCR to extract the plate numbers.

## 📁 Files Included

- `best.pt` – The trained YOLOv8 model.
- `predict_modified.py` – Script to run detection and OCR on a video.

## 📦 Requirements

Install required libraries using:

```bash
pip install ultralytics opencv-python easyocr torch
