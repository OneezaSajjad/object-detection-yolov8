# object-detection-yolov5
Object Detection with YOLOv5 | Self-Driving Car Project 
# Object Detection with YOLOv5 🚀
This repository contains my implementation of **object detection using YOLOv5**, developed as part of my **Final Year Project: Self-Driving Car with Motion Planning**.  
The system detects **cars, pedestrians, and other road obstacles** in real time and was tested on both PC and Raspberry Pi for autonomous driving applications.

---

## 🔧 Tech Stack
- **Language:** Python  
- **Framework:** PyTorch, Ultralytics YOLOv5  
- **Libraries:** OpenCV, NumPy, Matplotlib, Pandas  
- **Hardware:** Raspberry Pi 4, P3AT Camera Module, u-blox NEO-7M GPS  
- **Tools:** Jupyter Notebook, Miniconda/Anaconda
- ## 📂 Repository Structure
- bject-detection-yolov5/
│── README.md
│── LICENSE
│── data.yaml
│── requirements.txt
│
├── train/ # Training images
├── valid/ # Validation images
├── test/ # Test images
├── results/ # Sample detection results


---

## ⚙️ Installation
Clone the repository:
```bash
git clone https://github.com/OneezaSajjad/object-detection-yolov5.git
cd object-detection-yolov5
pip install -r requirements.txt
