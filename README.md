# ComputerVision-Project

# **Mugger Crocodile Biometric Identification**

## **Overview**
This project aims to automate the biometric identification of Mugger crocodiles (**Crocodylus palustris**) using deep learning techniques. The approach consists of a two-stage framework:

1. **YOLOv11** for object detection to generate bounding boxes around crocodile faces.
2. **ResNet18** for feature extraction, followed by a **FeatureNet module** for classification.

The model is trained on a dataset collected in different seasons to analyze how environmental variations impact performance.

---

## **Installation & Setup**
### **1. Clone the Repository**
```bash
$ git clone https://github.com/your-username/Mugger-Identification.git
$ cd Mugger-Identification
```

### **2. Create Virtual Environment & Install Dependencies**
```bash
$ python -m venv venv
$ source venv/bin/activate  # On Windows use `venv\Scripts\activate`
$ pip install -r requirements.txt
```
---

## **Results & Performance**
- **Accuracy:** 99.07%
- **True Positive Rate (TPR):** 0.9907
- **True Negative Rate (TNR):** 0.9999
- Confusion Matrix, per-class accuracy, and other performance metrics are stored in `outputs/`.

---

