# yolo-object-detection
# Object Detection with YOLOv5

This project implements an object detection pipeline using **YOLOv5**.  
It allows you to detect objects in images or videos, and outputs both annotated images (with bounding boxes) and detection metadata in JSON format.

---

## 🚀 Features
- Detects multiple object classes using YOLOv5.
- Outputs:
  - Annotated images with bounding boxes.
  - JSON files containing detection details (class, confidence, bounding box coordinates).
- Configurable thresholds for confidence and IoU.
- Easy to extend with new datasets or models.

---

## 📦 Installation

### Requirements
- Python 3.8+
- PyTorch with CUDA (if GPU acceleration is available)
- Dependencies from `requirements.txt`

Install dependencies:
```bash
pip install -r requirements.txt
