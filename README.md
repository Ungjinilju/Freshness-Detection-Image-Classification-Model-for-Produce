# **Freshness Detection: Image Classification Model for Produce**

This repository contains an image classification model designed to assess the freshness of produce. The project utilizes deep learning techniques to classify produce as either **fresh** or **rotten**, providing a valuable tool for quality control in agricultural and retail industries.

---

## 🚀 **Features**
- Classifies produce into **fresh** or **rotten** categories.
- Pre-trained models (e.g., **InceptionV3**, **Xception**) for enhanced accuracy.
- Supports custom datasets with automatic data preprocessing.
- Includes Grad-CAM visualization for interpreting model predictions.
- Modular structure for easy experimentation and model updates.
- Incorporates the [YOLOv5](https://github.com/ultralytics/yolov5) object detection model to identify produce.

---

## 📊 **Results**
- **Model Accuracy:** 93% on the validation dataset
- **Grad-CAM Insights:** Highlights the regions of the image that influenced predictions the most.
- **Performance Metrics:**
  - **Precision:** 93%
  - **Loss:** 0.2360
 
---

## 📝 **Steps Overview**

### Step 1: Freshness Classification (2 Classes)
- Classifies apples into fresh and rotten categories.
- Uses a binary classification model trained on apple images.
### Step 2: Multi-class Classification
- **Step 2-1**: Classifies 6 types of produce (e.g., apples, oranges, bananas, etc.) as either fresh or rotten (2 classes per produce type).
- **Step 2-2**: Classifies 9 types of produce (e.g., apples, oranges, bananas, etc.) into 18 classes (fresh or rotten for each type of produce).
### Step 3: YOLO-based Rotten Area Detection
- Uses YOLOv5 for detecting and calculating the rotten area on an apple.
- Calculates the percentage of the rotten area compared to the total apple area.
- Divides this percentage into 10 classes to assess the degree of rottenness.

---

## 🤝 **Contributing**
Contributions are always welcome! Whether it's fixing bugs, improving documentation, or suggesting new features, feel free to:

---

## 📜 **License**

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 📧 **Contact**
If you have questions, feedback, or suggestions, feel free to reach out:

- **Email:** yeohuiju03@gmail.com  
- **GitHub:** [Ungjinilju](https://github.com/Ungjinilju)

---

## 🌟 **Acknowledgments**

- Thanks to all contributors and collaborators who supported this project.
- This project leverages tools and frameworks such as:
  - **TensorFlow** for deep learning models
  - **Keras** for building and training models
  - **OpenCV** for image processing
  - **YOLOv5** for object detection ([Repository link](https://github.com/ultralytics/yolov5))
