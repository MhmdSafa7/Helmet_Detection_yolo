# Hard Hat Detection using YOLOv8

## Project Overview
This project implements an **object detection system** to identify **hard hats, persons, and heads** in images of construction workers. Using **YOLOv8**, the model detects safety compliance in real-time, providing a practical solution for construction site safety monitoring.

- **Dataset:** [Hard Hat Detection Dataset – Kaggle](https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection)  
- **Model:** YOLOv8 (Ultralytics)  
- **Languages/Libraries:** Python, PyTorch, OpenCV, Matplotlib, Scikit-learn  

---

## Dataset
The dataset contains annotated images of construction workers with bounding boxes for:

- **Helmet**  
- **Person**  
- **Head**  

**Dataset Stats:**  
- Number of images: ~3,000  
- Classes: 3  
- Annotation format: YOLO `.txt` files  

**Split:**  
- Train: 70%  
- Validation: 20%  
- Test: 10%  


