# Fire & Smoke Detection — YOLOv8 (UC17)

## Project Overview
A real-time fire and smoke detection system built using 
YOLOv8 as part of the Vision Technology Internship at 
St. John College of Engineering and Management.

## Results
| Metric | Score |
|--------|-------|
| mAP@0.5 | 66.3% |
| Fire mAP | 91.2% |
| Precision | 67.7% |
| Recall | 64.0% |
| Inference Speed | 4.4ms/image |

## Dataset
- 5068 original images
- 12,122 augmented images
- Classes: fire, smoke
- Source: Roboflow Universe

## Tech Stack
- YOLOv8n (Ultralytics)
- Google Colab (T4 GPU)
- Roboflow
- Python 3.12

## How To Run
```python
pip install ultralytics
from ultralytics import YOLO
model = YOLO('best.pt')
model.predict(source='your_image.jpg', show=True)
```

## Deployment
Model deployed on Roboflow:
(https://app.roboflow.com/space-3jvwp/fire-smoke-detection-1k8z9-vpblh/1)

## Internship
St. John College of Engineering and Management
Vision Technology Internship — UC17
