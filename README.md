# Pruning Point Detection in Apple Trees Using Computer Vision  

This project is a **Master’s thesis (University West, 2025)** by **Omid Saberi**, focusing on vision-based pruning point detection in apple trees. It develops a computer vision component using **YOLOv8** to detect candidate pruning points in RGB images, supporting precision orchard pruning, decision support, and future pruning automation.  

---

## 📌 Overview
Pruning in apple orchards is labour-intensive, time-critical, and requires expert judgment. This work explores how **deep learning and object detection** can provide interpretable, image-based decision support for pruning tasks.  

Key highlights:
- **YOLOv8m** object detector trained on a small annotated dataset  
- **Data curation & augmentation** (flips, rotations, scaling, photometric jitter)  
- **Evaluation** on a grouped validation split to avoid data leakage  
- Outputs include **on-image overlays** for operator review and machine-readable detections  
- Achieved **Precision: 0.864, Recall: 0.462, F1: 0.602, mAP@0.5: 0.602** on validation data  

---

## 🛠 Tools & Frameworks
- Python (Jupyter / Google Colab)  
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)  
- [Roboflow](https://roboflow.com/) – annotation and dataset management  
- [Albumentations](https://albumentations.ai/) – data augmentation  
- OpenCV, Pandas, Matplotlib – preprocessing and analysis  

---

## 📂 Repository Structure
